# Raspberry_TV_Box

General Design:
An browser embeded in Raspberry Pi which direct to media website like duonao or youtube. The basic operation for searching and watching video can be adapted to a bluetooth remote controller.

Basic Modules：
|   /* Similar to Web Crawler. Fetch the key content on website, such as thumbnail 
|      image of video, video link, search box. */
|-- Content Fetcher
|
|   /* Fill the page with fetched content. Using controller to browse the page and 
|      choose the content */
|-- Page System
|   |
|   |-- Page view
|   |
|   |-- Content Loader
|   |
|   |-- Page Control
|   |
|   |-- Video Player
|
\-- Bluetooth Process
