# WordPress Resume Blog Documentation
Part of Microsoft Student Accelerator project 2 as milestone in using Azure cloud services.

Link to WordPress resume blog: http://spacecorgicoding.azurewebsites.net/

## Plugin consideration and implementation

1.	SEO plugin : Yoast SEO
    - Benefits over other plugins: Feedback on readability/SEO analysis as edits are made, let author be conscious of word choice, preview of search appearance
    - High level implementation: Configuration wizard that has a simple and no-code interface to set up preferences for content type (Blog/forum/portfolio – chose portfolio for resume), author names
2.	Cache management plugin to improve site speed : W3 Total Cache
    - Benefits over other plugins: Simple one click access to perform a compatibility check or empty caches on the dashboard
    - High level implementation: Configuration settings to apply on page aches/browser caches/ cookie groups etc
3.	Analytics plugin to track traffic and user behavior : Google Analytics
    - Easy setup and installation using wizard
4.  Stylisation for home page : TypeEffect plugin
    - Benefit over css/js coding: easy UI to create style code snippet
    - High level implementation: Add in heading section with Elementor, use plugin dashboard to create text loop, copy and paste code snippet generated by plugin to as text to section
5. Customisation plugin / page builder :  Elementor
    - Benefit over original WordPress block editor / Divi : Elementor's drag and drop interface shows changes as you edit, although Divi provides back-end support, the interface in Elementor makes it easier to achieve low-code front end needs.
    - Implementation: buttons and motion effects that makes text sections fade in upon visiting page, stylisation to buttons to include icons and shadows
