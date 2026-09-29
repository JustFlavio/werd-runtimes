# Werd runtimes

Verified native runtime binaries for [Werd](https://github.com/JustFlavio/werd). Application installers, issues and the official roadmap live in the source repository.

Releases such as `php-8.5.11` contain macOS PHP CLI/FPM archives for Apple Silicon and Intel, with SHA-256 files and bundled license notices. Runtime versions are independent of Werd app versions.

The daily PHP workflow checks out the [build recipes](https://github.com/JustFlavio/werd/tree/main/scripts/php-builds) from the source repository and publishes here using this repository's `GITHUB_TOKEN`. Its canonical workflow template is `scripts/php-builds/workflow.yml` in that repository; copy changes here when updating the automation.

See [runtime provenance](https://github.com/JustFlavio/werd/blob/main/docs/runtime-sources.md) and the [runtime catalog](https://github.com/JustFlavio/werd/blob/main/catalog/catalog.json) for supported builds and checksums.
