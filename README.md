Berikut adalah isi terbaru dari README.md pada repo Sazwanismail:

````markdown name=README.md
- 👋 Hi, I’m @Sazwanismail
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Sazwanismail/Sazwanismail is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
---
title: About releases
intro: 'You can create a release to package software, along with release notes and links to binary files, for other people to use.'
redirect_from:
  - /articles/downloading-files-from-the-command-line
  - /articles/downloading-files-with-curl
  - /articles/about-releases
  - /articles/getting-the-download-count-for-your-releases
  - /github/administering-a-repository/getting-the-download-count-for-your-releases
  - /github/administering-a-repository/about-releases
  - /github/administering-a-repository/releasing-projects-on-github/about-releases
versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'
topics:
  - Repositories
---
## About releases

Releases are deployable software iterations you can package and make available for a wider audience to download and use.

Releases are based on [Git tags](https://git-scm.com/book/en/v2/Git-Basics-Tagging), which mark a specific point in your repository's history. A tag date may be different than a release date since[...]

You can receive notifications when new releases are published in a repository without receiving notifications about other updates to the repository. For more information, see [Managing notificatio[...]

Anyone with read access to a repository can view and compare releases, but only people with write permissions to a repository can manage releases. For more information, see [Managing releases](/re[...]

You can manually create release notes while managing a release. Alternatively, you can automatically generate release notes from a default template, or customize your own release notes template. F[...]

When viewing the details for a release, the creation date for each release asset is shown next to the release asset.

GitHub will automatically include links to download a zip file and a tarball containing the contents of the repository at the point of the tag's creation.

{% ifversion fpt or ghec %}
People with admin permissions to a repository can choose whether {% data variables.large_files.product_name_long %} ({% data variables.large_files.product_name_short %}) objects are included in th[...]

If a release fixes a security vulnerability, you should publish a security advisory in your repository. {% data variables.product.prodname_dotcom %} reviews each published security advisory and ma[...]

You can view the **Dependents** tab of the dependency graph to see which repositories and packages depend on code in your repository, and may therefore be affected by a new release. For more infor[...]

{% endif %}

You can also use the Releases API to gather information, such as the number of times people download a release asset. For more information, see [Releases API](/rest/releases).

{% ifversion fpt or ghec %}

## Storage and bandwidth quotas

Each file included in a release must be under {% data variables.large_files.max_file_size %}. There is no limit on the total size of a release, nor bandwidth usage.

{% endif %}

````
