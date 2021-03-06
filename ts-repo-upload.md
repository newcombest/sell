---

copyright:
  years: 2020, 2021
lastupdated: "2021-11-10"

keywords: troubleshoot software, HTTPS protocol, repo, github, tgz

subcollection: sell

content-type: troubleshoot

---

{:tsSymptoms: .tsSymptoms}
{:tsCauses: .tsCauses}
{:tsResolve: .tsResolve}
{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:external: target="_blank" .external}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:troubleshoot: data-hd-content-type='troubleshoot'}
{:beta: .beta}

# Why can't I upload my source details from my GitHub repository?
{: #repo-upload-error}
{: troubleshoot}

You receive the following error message when you try to upload your source details from a GitHub repository:
{: tsSymptoms}

`There was an error while contacting this URL.`

This error typically occurs because the repository doesn't support HTTPS protocol or your Helm chart repository does not include an `index.yaml` file. 
{: tsCauses}

Make sure that your repository supports HTTPS protocol and your repository includes an `index.yaml` file. Alternatively, you can also point directly to a `.tgz` release file, which you can generate in your public GitHub repository. For more information, see [Managing releases in a repository](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/managing-releases-in-a-repository){: external}.
{: tsResolve}
