# ``docctemplate``

Use DocC to build and share documentation for non-swift projects.
![](https://img.shields.io/github/stars/roblabs/swift-docc-template?label=Source&amp;style=social)

<!--@START_MENU_TOKEN@-->Summary paragaph<!--@END_MENU_TOKEN@-->

## Overview

<!--@START_MENU_TOKEN@-->Overview paragaph<!--@END_MENU_TOKEN@-->

## Topics

### <!--@START_MENU_TOKEN@-->Group<!--@END_MENU_TOKEN@-->

- <!--@START_MENU_TOKEN@-->TODO:  Update Topics<!--@END_MENU_TOKEN@-->

@Comment {
    // Useful Metadata directives
    //   copy/paste these directives into @Metadata

    @Comment {///}
    @Comment {/** --- */}
    @Comment {///}
    
    * https://www.swift.org/documentation/docc/technologyroot
    * @TechnologyRoot
      * Use `@TechnologyRoot` for "a documentation page that’s not associated with a particular framework."

    * https://www.swift.org/documentation/docc/pageimage
    @PageImage(purpose: icon, source: "PageImage", alt: "Alternative text that describes the image to screen readers.")
    @PageImage(purpose: icon, source: "avatar", alt: "Alternative text that describes the image to screen readers.")    
    
    * https://www.swift.org/documentation/docc/pagekind
    @PageKind(article)
    // or
    @PageKind(sampleCode)
    
    * https://www.swift.org/documentation/docc/calltoaction
    @CallToAction(url: "https://github.com/maplibre/maplibre-gl-js/releases/download/v3.5.0/dist.zip", purpose: download, label: "⬇️ Download")
    
    * https://www.swift.org/documentation/docc/titleheading
    * Replaces "Article" with this string
    @TitleHeading("MapLibre Release Oct 2023")
    
    * https://www.swift.org/documentation/docc/available
    @Available("MapLibre", introduced: "v3.5.0")
}
