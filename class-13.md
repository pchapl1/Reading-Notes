Its important to keep in mind if we are planning to use local storage, to do it in a well thought out way and never store user sensitive information in local storage.  Knowing

### Why would a developer use local storage for a web application?
    - if you want to keep information on a user but you dont want to force them to sign up for your service or app
    source: https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/

### What information should not be stored in local storage?
    - passwords or any kind of sensitive information

### Local storage can store what type of data? How would you convert it to that type before storing?
    - You can only store strings in different keys
    - You can store it as an object using json.stringify and parse it with json.parse

