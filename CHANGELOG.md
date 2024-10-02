# OIB Project Changelog

# 2024-09-03
## Updated
[**OIB Wiki**](https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/wiki)

A number of supporting docs have been moved to Wiki pages and removed from the repos to support a better documentation layout.

---

# 2024-10-02
Forked from (https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/)

Added Entra ID Groups

---

# 2024-09-02
## Releases
* [OIB MacOS v1.0](https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/releases/tag/macos-v1.0)
* [OIB Windows 365 v1.0](https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/releases/tag/win365-v1.0)
* [OIB Windows v3.3](https://github.com/SkipToTheEndpoint/OpenIntuneBaseline/releases/tag/windows-v3.3)

---

# 2024-08-29
## Added
**Repo Changelog**

Started this changelog to track changes to the whole repo to support the redesigned repo structure!

**Contributors**

Added [Contributors](CONTRIBUTORS.md) file to track contributors to the project, and the [contributors-readme-action](https://github.com/akhilmhdh/contributors-readme-action) to automatically update the the file with the contributors list.

## Changed
**Repo Structure**

To support the OIB expanding into new territories, the repo structure has been redesigned to support multiple OS's. Each OS will have its own folder, with OS-specific files (readme, changelog, baseline JSON's, supporting information etc.) contained within.
The root of the repo will now contain a README.md that will act as a "hub" for the project, linking to the various OS's and their respective README.md files.

As such, some of the files previously in the root of the repo have been moved to the WINDOWS folder.
