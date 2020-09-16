{
  "title": "SPL/IT",
  "date": "2020-09-15T12:42:05-05:00",
  "image": "/img/split.gif",
  "link": "https://github.com/SPL-IT-app/spl.it",
  "image": "/img/split.gif",
  "description": "$PL/IT is a mobile tab splitting app for friends who go out to eat but have different spending habits. iOS and Android users can upload photos of their receipts and claim ownership of each item in that receipt. Once the event is closed, each user is shown how much they should pay or charge other users in the event.",
  "tags": ["React Native","Firebase", "Google Cloud Vision API", "AWS"],
  "fact": "",
  "featured":true
}

$PL/IT is a mobile tab splitting app for friends who go out to eat but have different spending habits. iOS and Android users can upload photos of their receipts and claim ownership of each item in that receipt. Once the event is closed, each user is shown how much they should pay or charge other users in the event.

![SPL/IT](/img/split.gif "SPL/IT")

##### Development
This was built using Google's [Cloud Vision API](https://cloud.google.com/vision/docs/ocr) with a front end in [React Native](https://facebook.github.io/react-native/) and a back-end in [Firebase](https://firebase.google.com/).

We wrote a custom algorithm to parse the results from Cloud Vision's API into line items which we store in Firebase's real-time database. Firebase supports not only our app's database and authentication, but also user interaction. In addition, this non-relational database allows us to set up subscriptions to an SDK to handle queries almost instantly.

##### Contributors
* [Brittany Hill](https://github.com/ibrittanyhill)
* [Julianne Crawford](https://github.com/juliannemarik)
* [Lotus Tan](https://github.com/lotust)
* [Mustafa Dane](https://github.com/mustafadane)

