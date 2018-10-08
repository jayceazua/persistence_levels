# Research each of the following forms of persistence:

#### [LocalStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
1. Where this persistence lives?
    * saved across browser sessions
2. When the data would be deleted?
    * has no expiration time
3. At least three use cases for each?
    * You can add data into the LocalStorage: `.setItem()`
    * You can read data from the LocalStorage: `.getItem()`
    * You can either remove a specific item or clear: `removeItem()` && `clear()`

#### [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
1. Where this persistence lives?
    * In the user's computer
2. When the data would be deleted?
    * By default the cookie is destroyed when the current browser window is closed,  <br>
    but it can be made to persist for an arbitrary length of time after that.
3. At least three use cases for each?
    * used for general client-side storage
    * Session management - (*Logins, shopping carts, game scores, or anything else the server should remember*)
    * Personalization - (*User preferences, themes, and other settings*)
    * Tracking - (*Recording and analyzing user behavior*)

#### [SessionStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage)
1. Where this persistence lives?
    * Same as localStorage;
2. When the data would be deleted?
    * gets cleared when the page session ends; <br>
        A page session lasts for as long as the browser is open and survives over page reloads and restores.
3. At least three use cases for each?
    * You can add data into the SessionStorage: `.setItem()`
    * You can read data from the SessionStorage: `.getItem()`
    * You can either remove a specific item or clear: `removeItem()` && `clear()`

#### [Sessions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/sessions/Session)
1. Where this persistence lives?
    * web browser in "memory/ redis, or database"
2. When the data would be deleted?
    * You can set the expiration time or just manually delete
3. At least three use cases for each?
    * It's a way that web servers keeps tracks of user data
    * collect and store the data through JWTokens on the backend
    * keeping track if the user logged in or out

#### [Client-side cache](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)
1. Where this persistence lives?
    * in a folder in your computer system (*web browser*) temporary memory storage.
2. When the data would be deleted?
    * when you manually clear browser cache (*browser option settings*)
3. At least three use cases for each?
    * avoid transferring the same data over the network repeatedly
    * reduce network traffic and latency
    * Think CDNS

#### [Server-side cache](https://www.digitalocean.com/community/tutorials/web-caching-basics-terminology-http-headers-and-caching-strategies)
1. Where this persistence lives?
    * server itself
2. When the data would be deleted?
    * manually whenever you clear the server of the stored data
3. At least three use cases for each?
    * accelerate application performance
    * stores it longer in memory than client-side
    * increases speed of loading heavier data

#### Remote Cache
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### Remote Services
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### Database
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?
