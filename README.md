# MediaStreamTrack API for Insertable Streams of Media

also known as Breakout Box

(not to be confused with the MediaStreams API)

This repository contains a **proposal** for an API that allows the
insertion of user-defined processing steps in the pipeline that
handles raw media using a MediastreamTrack

In order to allow such processing, it defines a number of extensions
to the objects defined in [MEDIACAPTURE-MAIN](https://w3c.github.io/mediacapture-main/), and also
draws upon definitions from [WEB-CODECS](https://github.com/WICG/web-codecs).


To modify the specification, please update `index.bs` from which the HTML document is automatically generated using [Bikeshed](https://tabatkins.github.io/bikeshed/).