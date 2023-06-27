## News-Portal ##

This README would normally document whatever steps are necessary to get your application up and running.

### What is News-Portal? ###
* Project set up for our interview candidates.

### How do I get set up? ###

* ### Summary of set up

Run the below command to clone the pigeon-UI repository.
```
  git clone https://github.com/Ankitskyt/newsportal.git
```
Run the below command to install the dependencies in this project.
```
npm i
```

Run the below command to build the project.
```
npm build
```
Run the below command to run the application.
```
npm start
```
The application should be up and running in the port 3000

API for UPI news: https://api.newscatcherapi.com/v2/search?q=UPI
API for ISRO news: https://api.newscatcherapi.com/v2/search?q=ISRO

API Key: k1JEO6EGWczlbAHwh5ICMPzTASZ5_rcFexifwr8nNnM

Response Format:

```
{
    "status": "ok",
    "total_hits": 2150,
    "page": 1,
    "total_pages": 43,
    "page_size": 50,
    "articles": [
        {
            "title": "UPI LITE Is The New Sensation As It Makes Small Payments Secure And Easier",
            "author": "Business Desk",
            "published_date": "2023-06-21 05:22:02",
            "published_date_precision": "full",
            "link": "https://www.news18.com/business/upi-lite-is-the-new-sensation-as-it-makes-small-payments-secure-and-easier-8132623.html",
            "clean_url": "news18.com",
            "excerpt": "UPI LITE made instant transactions up to Rs 200 without using a PIN through a wallet linked to a bank account.",
            "summary": "UPI LITE, a new feature introduced by the National Payments Corporation of India, aims to enhance the convenience of small UPI transactions. This feature allows users to make payments with just a single click, eliminating the need for multiple steps. UPI, launched by the Reserve Bank of India in September 2022, has gained significant popularity since its inception, and the BHIM app has been facilitating UPI transactions since the end of September last year.\nIn UPI LITE, users have the option to utilise an on-device wallet instead of linking a bank account.",
            "rights": "news18.com",
            "rank": 2238,
            "topic": "business",
            "country": "IN",
            "language": "en",
            "authors": "Business Desk",
            "media": "https://images.news18.com/ibnlive/uploads/2023/06/untitled-design-2023-06-21t104833.369-168732472316x9.jpg",
            "is_opinion": false,
            "twitter_account": "@cnnnews18",
            "_score": 17.869492,
            "_id": "f9708b6110f315e47d6c6c30345d1fbe"
        },
        ........
    ]
}
