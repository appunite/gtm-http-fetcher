Information on using the Google Toolbox for Mac HTTP Fetcher project 
is available at

http://code.google.com/p/gtm-http-fetcher/

INSTALATION on iPhone:

in your project directory:
git submodule add git@github.com:appunite/gtm-http-fetcher.git Frameworks/GTMHTTPFetcher

drag your Frameworks/GTMHTTPFetcher/Source/GTMHTTPFetcher.xcodeproj file to your project

add GTMHTTPFetcherLib (GTMHTTPFetcher) to your "Target dependences"

add "libGTMHTTPFetcher.a" to your "Link Binary With Libraries"

add "$(SOURCE_ROOT)/Frameworks/GTMHTTPFetcher/Source/Build" to your "Header Search Path"


