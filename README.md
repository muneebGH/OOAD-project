# CIA-country-data-crawler

## Build dependencies :

- JSoup [Download](https://jsoup.org/packages/jsoup-1.13.1.jar)

## Runtime dependencies

- good internet connection ( _for the crawler_ ). Crawling and scraping will consume time because there are 267 links as there are 267 countries on cia website and it gets URL of each of 267 then makes connection, loads HTML of that link then starts parsing and populating. **Have Patience**


### Steps to run project :

1. Download Project and save in files.
2. Open with Intelli-j idea
3. Download dependencies
4. goto File -> Project Structure -> Libraries -> click (+) to add dependency
5. Apply and run Application.main()

**Recommended IDE - _Intelli j Idea_**

### Possible Issues (Windows)
##### No Run Icon on Application.main() 
   - Right-click a folder in the Project tool window.
   - Select Mark Directory as from the context menu.
   - Select the Sources root
   - File -> Project Structure -> project & **Make sure that _Compiler output path_ is set**
#### java release version 13 not supported
   - goto File -> Project Structure -> Modules -> language level 
   - change language level from 13 to 12

## DEMO

- #### loading
  ![loading screen](app/imgs/splash.png)
- #### App
  ![App home](app/imgs/app.png)
