# TextMate bundle for Liquid development

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/shopify/liquid-tmbundle.git "Liquid.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/shopify/liquid-tmbundle/tarball/main
    tar zxf shopify-liquid-tmbundle*.tar.gz
    rm shopify-liquid-tmbundle*.tar.gz
    mv shopify-liquid-tmbundle* "Liquid.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Mirrored from: <http://blog.radixhound.com/2007/1/31/liquid-textmate-bundle>
