# apify-projects
## Realtor Agents Scraper Pro 🧲
#### Welcome to Realtor Agents Scraper Pro 🎉

### ✨ About This Actor ✨
The Realtor Agents Scraper Pro is a powerful tool that enables you to extract valuable data from Realtor's website, even though it lacks an API. This tool is specifically designed to help you overcome data retrieval challenges and gain insights for your real estate business.


One of the key features of the Realtor Agents Scraper Pro is its ability to scrape detailed information on agent profiles. With this tool, you can extract important details such as contact information, recent listings and more. This information can be used for a variety of purposes, including lead generation, market research, and competitive analysis.


## ✨ How to use it ✨📍

To use this scraper tool, follow these steps:

#### 📌 Step-1

First, navigate to "https://www.realtor.com/realestateagents/" in your web browser.

![alt text](https://cdn.nar.realtor/sites/default/files/migration_files/images/logos/NAR/2015-realtorcom-logo-600px.jpg)
            
            
### 📌 Step-2

Next, enter the city or zip code that you want to search for agents in.

![alt text](https://support.realtor.com/servlet/rtaImage?eid=ka53a000000LBOt&feoid=00N3a00000D2DC5&refid=0EM3a000001Awgb)


### 📌Step-3

  1. Once you have entered your search criteria, the website will display a list of agents that match your search.

  2. Copy the URL of the search results page from your browser's address bar.



### 📌 Step-4

In the input area of the scraper tool, paste the URL you just copied into the "Start URLs" field



### 📌 step-5

Once you have pasted the search results page URL into the scraper tool and configured any desired settings, you can run the scraper to start extracting data from the page. Depending on the size of the page and the complexity of the data you are extracting, the scraper may take a few minutes to complete.

Once the scraper has finished, you will be able to download the extracted data in a variety of formats, including CSV, Excel, JSON, HTML, and more. Simply select the format you prefer and download the file to your computer. With the scraped data in hand, you can use it to gain insights and make informed decisions for your real estate business.

![alt text](https://cdn.filestackcontent.com/NHeE3XlMRCAvA94aEnVL)



## Output: 📊☑️
And here is the same data but in JSON. You can choose in which format to download your Realtor data: JSON, JSONL, Excel spreadsheet, HTML table, CSV, or XML.
Output with more 290+ entries this only for one agent:

```python

[
  {
    "address": {
      "line": "9036 CALIFORNIA CITY BLVD",
      "line2": "",
      "city": "CALIFORNIA CITY",
      "postal_code": "93505",
      "state_code": "CA",
      "state": "",
      "country": "US"
    },
    "advertiser_id": 2174646,
    "agent_rating": 5,
    "background_photo": {
      "href": ""
    },
    "broker": {
      "fulfillment_id": 0,
      "designations": [],
      "name": "",
      "accent_color": "",
      "photo": {
        "href": ""
      },
      "video": ""
    },
    "description": "",
    "designations": [],
    "first_month": 0,
    "first_name": "",
    "first_year": 2002,
    "has_photo": true,
    "href": "",
    "id": "56d6bc0ade071e0100641343",
    "is_realtor": true,
    "languages": [],
    "last_name": "",
    "last_updated": "Mon, 01 May 2023 22:01:05 GMT",
    "marketing_area_cities": [
      {
        "city_state": "California City_CA",
        "name": "California City",
        "state_code": "CA"
      },
      {
        "city_state": "Hi Vista_CA",
        "name": "Hi Vista",
        "state_code": "CA"
      },
      {
        "city_state": "Lancaster_CA",
        "name": "Lancaster",
        "state_code": "CA"
      },
      {
        "city_state": "Palmdale_CA",
        "name": "Palmdale",
        "state_code": "CA"
      },
      {
        "city_state": "Lake Los Angeles_CA",
        "name": "Lake Los Angeles",
        "state_code": "CA"
      }
    ],
    "mls": [
      {
        "member": {
          "id": "FAR_158D165D0032"
        },
        "abbreviation": "FAR_199B1A4E",
        "type": "A",
        "primary": true,
        "license_number": "01330709"
      }
    ],
    "mls_history": [
      {
        "member": {
          "id": "FAR_1BD513FF158F"
        },
        "inactivation_date": "2022-04-15T17:48:14.000Z",
        "abbreviation": "FAR_1BE91A4E",
        "type": "A",
        "primary": false,
        "license_number": "01330709"
      }
    ],
    "nar_only": 1,
    "nick_name": "",
    "nrds_id": "571798438",
    "office": {
      "name": "Mamayan Realty Inc",
      "mls": [
        {
          "member": {
            "id": "FAR_158D13A0"
          },
          "abbreviation": "FAR_199B1A4E",
          "type": "O",
          "primary": "true"
        }
      ],
      "phones": [
        {
          "ext": null,
          "number": "(760) 37*-****",
          "type": "Office"
        }
      ],
      "phone_list": {
        "phone_1": {
          "number": "760*7****",
          "type": "Office"
        }
      },
      "photo": {
        "href": ""
      },
      "slogan": "",
      "video": "",
      "fulfillment_id": 0,
      "address": {
        "line": "9036 CALIFORNIA CITY BLVD",
        "line2": "",
        "city": "CALIFORNIA CITY",
        "postal_code": "93505",
        "state_code": "CA",
        "state": "",
        "country": "US"
      },
      "party_id": "110292605",
      "website": "",
      "feed_licenses": [],
      "licenses": []
    },
    "party_id": 3309609,
    "person_name": "George Mamayan",
    "phones": [
      {
        "ext": "",
        "number": "(818) 9*4-7***",
        "type": "Mobile"
      }
    ],
    "photo": {
      "href": "http://p.rdcpix.com/v02/ab62e2100-c0l.jpg"
    },
    "recommendations_count": 0,
    "review_count": 1,
    "role": "agent",
    "served_areas": [
      {
        "name": "California City",
        "state_code": "CA"
      },
      {
        "name": "Lancaster",
        "state_code": "CA"
      }
    ],
    "settings": {
      "share_contacts": false,
      "full_access": false,
      "display_listings": true,
      "far_override": false,
      "show_stream": false,
      "terms_of_use": false,
      "has_dotrealtor": false,
      "display_sold_listings": true,
      "display_price_range": true,
      "display_ratings": false,
      "loaded_from_sb": false,
      "broker_data_feed_opt_out": false,
      "unsubscribe": {
        "autorecs": false,
        "recapprove": false,
        "account_notify": false
      },
      "new_feature_popup_closed": {
        "agent_left_nav_avatar_to_profile": false
      },
      "profile_wizard": {
        "realsatisfied_opt_out": false,
        "tt_opt_out": false
      },
      "reviews_opt_out": {
        "rdc": true,
        "rs": true
      }
    },
    "slogan": "Broker",
    "specializations": [],
    "title": "Broker",
    "types": "agent",
    "user_languages": [],
    "web_url": "https://www.realtor.com/realestateagents/George-Mamayan_CALIFORNIA-CITY_CA_2174646_571798438",
    "zips": [
      "93505",
      "93535"
    ],
    "name": "George Mamayan, Broker",
    "full_name": "George Mamayan",
    "feed_licenses": [
      {
        "country": "US",
        "state_code": "CA",
        "license_number": "01****09"
      }
    ],
    "for_sale_price": {
      "count": 42,
      "min": 3200,
      "max": 1750000,
      "last_listing_date": "2023-05-11T04:56:51Z"
    },
    "recently_sold": {
      "count": 93,
      "min": 2500,
      "max": 375000,
      "last_sold_date": "2023-03-31"
    },
    "agent_team_details": {
      "is_team_member": false
    },
    "lang": {
      "srp_content": {
        "enter_name": "Enter Name",
        "enter_email": "Enter Email",
        "homeowner_looking_sell": "Are you a homeowner looking to sell?",
        "track_your_home_and_get_access_title": "Track your home and get access to:",
        "track_your_home_and_get_access_list_item_1": "Updates on your home's value",
        "track_your_home_and_get_access_list_item_2": "Comparables and market trends",
        "track_your_home_and_get_access_list_item_3": "Information on your current outstanding principal",
        "go_to_my_home": "Go to My home",
        "realtors": "REALTORS",
        "realtor": "REALTOR",
        "found": "found",
        "active_realtors": "Active Realtors",
        "map_of_active": "map of Active",
        "realtor_found": "count_dyn REALTORS® found",
        "postal_code_search": "zipcode_dyn REALTORS® & Real Estate Agents",
        "name_of_realtor": "Name of REALTOR®",
        "sort_by": "Sort by",
        "rating": "Rating",
        "recommendation": "Recommendation",
        "price_range": "Price Range",
        "more_filters": "More Filters",
        "show_agents_with": "Show Agents With",
        "photos": "Photos",
        "worked_with": "Worked with",
        "buyers_and_sellers": "Buyers and Sellers",
        "buyers": "Buyers",
        "sellers": "Sellers",
        "additional_languages": "Additional Languages",
        "certifications_and_designations": "Credentials",
        "homes_priced_from": "Homes Priced From",
        "min_price": "Min Price",
        "max_price": "Max Price",
        "any": "Any",
        "most_recent_activity": "Most Recent Activity",
        "highest_ratings": "Highest Ratings",
        "most_recommendations": "Most Recommendations",
        "most_for_sale_listings_local": "Most For Sale Listings (Local)",
        "most_for_sale_listings_all": "Most For Sale Listings (All)",
        "most_sold_listings_local": "Most Sold Listings (Local)",
        "most_sold_listings_all": "Most Sold Listings (All)",
        "viewing": "Viewing",
        "view": "View",
        "home": "Home",
        "find_realtor": "find REALTORS®",
        "list": "List",
        "activity_map": "Activity Map",
        "for_sale": "For Sale",
        "years": "years",
        "months": "months",
        "month": "month",
        "recently_sold": "Recently Sold",
        "sold": "Sold",
        "activity_range": "Activity range",
        "listed_a_house": "Listed a house",
        "languages": "Languages",
        "years_of_experience": "Years of experience",
        "experience": "Experience",
        "view_local_activity_map": "View Local Activity Map",
        "local_map": "Local Map",
        "Recommendations": "Recommendations",
        "recommendations": "recommendations",
        "local": "Local",
        "next": "Next",
        "cancel": "Cancel",
        "close": "Close",
        "how_to_select_a_realtor": "How to Select a REALTOR",
        "use_find_realtor": "Use the \"Find a Realtor®\"",
        "search_engine_on_realtor": "search engine on realtor.com to find individuals who actively sell in your community.",
        "get_recommendations": "Get recommendations from friends and family members who have bought or sold their properties recently.",
        "look_for_realtor_signs_in_community": "Look for REALTOR®  signs in your community.",
        "attend_open_house": "Attend open houses and see if you connect with a REALTOR",
        "call_brokerage": "Call your neighborhood real estate brokerages.",
        "read_more": "Read More",
        "everyone_is_reading": "Everyone's Reading",
        "find_right_real_estate_agent": "How to Find the Right Real Estate Agent",
        "first_time_home_buyer_resource_center": "First-Time Home Buyer Resource Center",
        "complete_guide_to_selling_your_house": "The Complete Guide to Selling Your Home",
        "estimate_your_home_value": "Estimate your home's value",
        "road_and_stake_park": "on the Road and a Skate Park on Lil Wayne's Roof",
        "compare_home_loan_and_get_preapproved": "Compare home loan’s and get pre-approved",
        "agent_details": "Agent Details",
        "listing_agent": "Listing Agent",
        "buyers_agent": "Buyer's Agent",
        "listed_days_ago": "Listed [days] days ago",
        "days": "days ",
        "ago": "ago",
        "search_not_found": "Sorry! We couldn't find any REALTORS® that matched your search criteria. Please adjust your search criteria and try again!",
        "properties_in_last_24_months": "who have at least one property for sale OR have sold/bought one or more properties in the past 24 months",
        "agents_with_photos": "Only agents with photos are shown. Use",
        "to_adjust_results": "to adjust your results.",
        "this_map_shows": "This map shows active REALTORS",
        "in_the_area": "in the area",
        "sort": "Sort",
        "none_reported": "None Reported",
        "view_full_profile": "View Full Profile",
        "view_details": "View Details",
        "view_more": "View More",
        "listed": "Listed",
        "activity": "Activity",
        "sold_price_not_disclosed": "Sold Price Not Disclosed",
        "see_agents_near_by_property": "See agent's nearby properties",
        "hide": "Hide",
        "ask_a_realtor": "Ask a REALTOR®",
        "get_in_touch_with": "Get in touch with",
        "your_name": "Your Name",
        "your_phone": "Phone",
        "your_email": "Your Email",
        "your_message": "Your Message",
        "send": "Send",
        "agent_success_message": "You successfully messaged your selected agents. Expect a response soon!",
        "call_agent": "Call Agent",
        "team": "Team",
        "transactions": "Transactions",
        "up": "Up",
        "clear": "Clear",
        "to": "To",
        "name": "Name",
        "get_started": "Get Started",
        "number_of_recommendations": "Number of Recommendations",
        "search": "Search",
        "map": "Map",
        "activity_map_for_this_agent": "Activity map for this agent is available only when he/she has recent activity in the searched city within the past 24 months.",
        "use_the": "Use The ",
        "find_a_realtor": "Find a Realtor",
        "please_zoom_in": "Please zoom in or click on cluster pins to see more detail",
        "activity_map_display": "The activity map displays only active<sup>*</sup> agents. Click on agent pin for more details on agent's activity.",
        "active_agents_definition": "Active agents are ones who have at least one property for sale OR have sold/bought one or more properties in the past 24 months.",
        "activity_map_and_agent_list": "The activity map and agent list display only active* agents. Click on agent card or agent pin for more details on agent's activity.",
        "right_now": "right now!",
        "sort_your_agent_lists_by": "Sort your agent lists by:",
        "back_to_search": "Back to Search",
        "most_recent_activity_definition": "Most Recent Activity - agents with most recent listings or sold transactions shown first",
        "highest_ratings_definition": "Highest Ratings - agents with the highest ratings shown first",
        "most_recommendations_definition": "Most Recommendations - agents with highest number of recommendations shown first",
        "most_for_sale_listings_local_definition": "Most For Sale Listings (Local) - agents with the most listings for sale in local market (city or zipcode) shown first ",
        "most_for_sale_listings_all_definition": "Most For Sale Listings (All) - agents with the most listings for sale in all markets shown first ",
        "most_sold_listings_local_definition": "Most Sold Listings (Local) - agents with most sold listings in local market (city or zipcode) shown first",
        "most_sold_listings_all_definition": "Most Sold Listings (All) - agents with most sold listings in all markets shown first",
        "worked_with_seller_and_buyer": "Worked with Seller and Buyer",
        "worked_with_buyer": "Worked with Buyer",
        "worked_with_seller": "Worked with Seller",
        "geolinking_caption": "Real Estate Agents Near",
        "real_estate_agents": "Real Estate Agents",
        "geolinking_sub_caption": "ZIPS near",
        "city_linking_text": "Agents",
        "zip_linking_text": "Agents in",
        "agent_popular_city_caption": "Search Agents in Popular Cities",
        "selected_sorted": {
          "sort-activity": "Most Recent Activity",
          "sort-activelistingsLocal": "Most For Sale Listings (Local)",
          "sort-activelistings": "Most For Sale Listings (All)",
          "sort-recommendations": "Most Recommendations",
          "sort-soldLocal": "Most Sold Listings (Local)",
          "sort-sold": "Most Sold Listings (All)",
          "sort-ratings": "Highest Ratings"
        },
        "the_reading_room_realtor": "REALTORS",
        "sold_a_house": "Sold a house",
        "and_up": "&amp; Up",
        "realtors_found": "[count] REALTORS® found",
        "map_of_active_part1": "Map of active",
        "map_of_active_part2": "",
        "map_active_realtors_dropdown_1": "Active REALTORS® who have at least one property for sale OR have sold/bought one or more properties in the past 24 months"
      }
    }
  }
]
```

## ✨ Maximize Efficiency: Realtor Agents Scraper Pro with Apify API ✨


The Apify API empowers you with programmatic access to the comprehensive Apify platform. With RESTful HTTP endpoints at your disposal, you can effortlessly manage, schedule, and execute Apify actors. Additionally, the API facilitates seamless access to datasets, performance monitoring, result retrieval, version creation, updates, and much more.

Leverage the apify-client NPM package to tap into the API using Node.js, or employ the apify-client PyPI package for Python integration.

For comprehensive information, explore the Apify API reference [documentation](https://docs.apify.com/api/v2), or simply click on the API tab to explore insightful code examples.


## 💬 Feedback 💬

If you have any technical feedback or encountered a bug while using the Realtor Agents Scraper Pro Scraper, please create an issue on the actor's dedicated ["Issues"](https://console.apify.com/actors/nH3BMQQSYrggfXNfi/issues) tab in the Apify Console. We value your input and appreciate your help in improving our services.
