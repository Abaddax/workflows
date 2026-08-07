# Abaddax.Build.Common

This project contains some common build settings for C# projects.
These include, for example, an `.editorconfig`, which can be automatically integrated via the NuGet package.

# Features
* Automatic NuGet-refernce to `Microsoft.SourceLink.GitHub`
* Automatic NuGet-refernce to `Microsoft.VisualStudio.Threading.Analyzers`
* Common csproj-settings for NuGet publishing
* Enforced csproj settings:
    * `Authors`
    * `PackageLicenseFile`/`PackageLicenseExpression`
    * `RepositoryUrl`
* Automatic `.editorconfig`
    * disable via `<EnforceEditorConfig>false</EnforceEditorConfig>`
* Ensured `.gitignore`
    * disable via `<EnforceGitignore>false</EnforceGitignore>`
* Other common settings
    * disable via `<AbaddaxDefaults>false</AbaddaxDefaults>` 



