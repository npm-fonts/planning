# planning
scoping this out

* prereqs
  * [ ] abstract out the release script from generator-iojs

* google fetch script
 * Hit the google API for all avaliable fonts. https://developers.google.com/fonts/docs/developer_api
   * will have to do this once per UA https://neverpanic.de/blog/2014/03/19/downloading-google-web-fonts-for-local-hosting/
   * will want to output an array in a standarized format so our script module can consume more than just google fonts
 * create repo script: example output: https://github.com/joeybaker/font-nunito
   * accept a standard input
   * find/create a new repo: accept an option that is the directory to do this in
     * init a new module if necessary under the `@font` scope
     * standard keywords: font, <fontname>, css, font style (sans, serif, etc)
     * need a standardized readme that lists each font style
   * make a css file for each style, include each font source
   * make an index file
   * commit and release
