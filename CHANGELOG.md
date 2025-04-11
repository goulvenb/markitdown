# Changelog

## 1.0.0 (2025-04-11)


### Features

* add argument parsing and setup.py file for cli tool capability ([33638f1](https://github.com/goulvenb/markitdown/commit/33638f1fe6d380a888f7d9bf5119dba965fba3c3))
* add devcontainer configuration and installation script ([07fe457](https://github.com/goulvenb/markitdown/commit/07fe457a9033baf9a534258105488f0b57853f7d))
* Add IpynbConverter ([7900314](https://github.com/goulvenb/markitdown/commit/790031409bcfe0cd9393c3a5d58cb3bb7e317651))
* Add IpynbConverter ([a3208f2](https://github.com/goulvenb/markitdown/commit/a3208f2bd059997634a7a1a5b0115b0a730b7bdd))
* add project description in pyproject.toml ([c86287b](https://github.com/goulvenb/markitdown/commit/c86287b7e3c6b41138c9b8e5e9097c359ea32fbc))
* add rss converter ([53fad6e](https://github.com/goulvenb/markitdown/commit/53fad6eb3149eba21fcf1d6d3cbace6e8621a995))
* Add RSSConverter ([ddf695c](https://github.com/goulvenb/markitdown/commit/ddf695cf819b13c908a3d9c1fcab94ecb1ea4eb2))
* add tests of rss convertor ([752fbd3](https://github.com/goulvenb/markitdown/commit/752fbd333c71b300b7d5c67e733be74d52362eeb))
* add version option to markitdown CLI ([#172](https://github.com/goulvenb/markitdown/issues/172)) ([cfd2319](https://github.com/goulvenb/markitdown/commit/cfd2319c14a1ed0be6f5a89e145f18878803fa7e))
* **devcontainer:** Add DevContainer Configuration for Easier Contribution Setup ([41a10b9](https://github.com/goulvenb/markitdown/commit/41a10b9a35b3b85dcb15bd2b5aa5f39c15c05a30))
* **docker:** improve dockerfile build ([#220](https://github.com/goulvenb/markitdown/issues/220)) ([515fa85](https://github.com/goulvenb/markitdown/commit/515fa854bfcbd1b94d999690ef8945c8b96c75cb))
* enable Git support in devcontainer ([#136](https://github.com/goulvenb/markitdown/issues/136)) ([f94d099](https://github.com/goulvenb/markitdown/commit/f94d09990ef6ccb9d7d94800dbec4b5068504055))
* outlook ".msg" file converter ([#196](https://github.com/goulvenb/markitdown/issues/196)) ([d248621](https://github.com/goulvenb/markitdown/commit/d248621ba4e7f4f91dba22c000a17c62b394d0c1))
* **pptx:** support image description with LLM for pptx files ([#306](https://github.com/goulvenb/markitdown/issues/306)) ([7cf5e0b](https://github.com/goulvenb/markitdown/commit/7cf5e0bb23980cd004ceeea476c1bde3246d3c84))
* render math equations in .docx documents ([#1160](https://github.com/goulvenb/markitdown/issues/1160)) ([3fcd48c](https://github.com/goulvenb/markitdown/commit/3fcd48cdfc651cbf508071c8d2fb7d82aeb075de))
* sort pptx shapes to be parsed in top-to-bottom, left-to-right order ([#1104](https://github.com/goulvenb/markitdown/issues/1104)) ([0229ff6](https://github.com/goulvenb/markitdown/commit/0229ff6cb75aa63e5ba6582766d0e5b9cba1fdfa))
* support convert atom to markdown ([7dc2695](https://github.com/goulvenb/markitdown/commit/7dc2695b9614f16493886bfd7155c490083f180e))


### Bug Fixes

* argparse CLI option ordering, fixes [#268](https://github.com/goulvenb/markitdown/issues/268) ([#290](https://github.com/goulvenb/markitdown/issues/290)) ([2a4f7bb](https://github.com/goulvenb/markitdown/commit/2a4f7bb6a8e3a5a4bd73e0dcfe1849205f62708a))
* correct f-string formatting in FileConversionException ([#1121](https://github.com/goulvenb/markitdown/issues/1121)) ([75140a9](https://github.com/goulvenb/markitdown/commit/75140a90e2f78b44061c1798d7ece2995559bd9d))
* Implement retry logic for YouTube transcript fetching and fix URL decoding issue ([#1035](https://github.com/goulvenb/markitdown/issues/1035)) ([a394cc7](https://github.com/goulvenb/markitdown/commit/a394cc7c2738c8b5395fd2c55824e3d85cd6307d))
* prevent path traversal vulnerabilities in ZipConverter ([6e4caac](https://github.com/goulvenb/markitdown/commit/6e4caac70d63c87a532be773b2dc3f330f9fdbda))
* **README:** correct pip install command formatting ([#1090](https://github.com/goulvenb/markitdown/issues/1090)) ([80baa5d](https://github.com/goulvenb/markitdown/commit/80baa5db18e6133965dc9ac47bbebf734808ed7e))
* support -o param to avoid encoding issues ([#116](https://github.com/goulvenb/markitdown/issues/116)) ([1123392](https://github.com/goulvenb/markitdown/commit/1123392306bf14c40610bef2773d7a7b01ffbc05))
* **transcription:** IS_AUDIO_TRANSCRIPTION_CAPABLE should be iniztialized ([#194](https://github.com/goulvenb/markitdown/issues/194)) ([4678c8a](https://github.com/goulvenb/markitdown/commit/4678c8a2a4c5f2984b2a8b3051b0376cf0c2bec4))
