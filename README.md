# LaTeX Table Viewer Endpoint

## Background

This is the endpoint container that is accessed by the [LaTeX Table Viewer](https://github.com/adamkaplan0/latextableviewer) app for downloading all of the necessary TeXLive files. It is essentially a direct copy of the [SwiftLaTeX back-end](https://github.com/SwiftLaTeX/Texlive-Ondemand) with the small modification of changing and exposing the port to 80 in the Dockerfile. This allows me to deploy it directly to my cloud service provider.
