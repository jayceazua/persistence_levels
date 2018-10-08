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
    * By default the cookie is destroyed when the current browser window is closed,  \n
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
    * gets cleared when the page session ends; \n
        A page session lasts for as long as the browser is open and survives over page reloads and restores. 
3. At least three use cases for each?
    * You can add data into the SessionStorage: `.setItem()`
    * You can read data from the SessionStorage: `.getItem()`
    * You can either remove a specific item or clear: `removeItem()` && `clear()`

#### Sessions
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### A Database
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### Client-side cache
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### Serve-side cache
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### A remote cache (e.g. Redis)
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?

#### A remote services (e.g. AWS S3, RabbitMQ, PubNub)
1. Where this persistence lives?
2. When the data would be deleted?
3. At least three use cases for each?
