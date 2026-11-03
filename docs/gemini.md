# Gemini CLI preparation

The manifest is at the extension root. It uses httpUrl for Streamable HTTP,
includes only the three public guidance tools and requests no secrets or trust
bypass. GEMINI.md carries the public workflow; the skill is also bundled.

On an existing authorized Gemini CLI: `gemini extensions validate /absolute/path/to/submitsignal-form-guide`.
A syntax validation is not a model workflow test. Temporary supported install:
`gemini extensions install /absolute/path/to/submitsignal-form-guide`.
Review the requested permissions in the normal prompt. Run the shared cases in
fresh sessions restricted to this extension, then uninstall this exact extension
once. Do not modify unrelated installed extensions or authentication.

For the public gallery, publish a reviewed repository with gemini-extension.json
at the absolute root and the gemini-cli-extension GitHub topic. The gallery crawls
tagged public repositories and applies validation; no listing has been created.
No repository URL has been invented for this preparation.
