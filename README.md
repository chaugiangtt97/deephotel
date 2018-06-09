# Only Scraping Hotel's Info @TripAdvisor.jp, Booking.com

Python Function To Scrape Info is Hotel's Name, Address, Review Text, Score, and so on.

Based on "https://github.com/monkeylearn/hotel-review-analysis"

Special thanks to @monkeylearn

## crawl to review-text of hotels in kyoto @TripAdvisor.jp
scrapy crawl tripadvisor_review -a start_url="https://www.booking.com/searchresults.ja.html?city=-240905;ss=%E5%A4%A7%E9%98%AA%E5%B8%82" -o <file name>.csv

## crawl to review-score of hotels in kyoto @TripAdvisor.jp
scrapy crawl tripadvisor_score -a start_url="https://www.tripadvisor.jp/Hotels-g298564-Kyoto_Kyoto_Prefecture_Kinki-Hotels.html' -o <file name>.csv

As you know, I'm Python Beginner.
I'm glad you to give feedback.

Thank you for @monkeylearn!!
## crawl to review-text of hotels in osaka @Booking.com
scrapy crawl booking_review -a start_url="https://www.booking.com/searchresults.ja.html?city=-240905;ss=%E5%A4%A7%E9%98%AA%E5%B8%82" -o osaka180609review_bk.csv


## crawl to review-score of hotels in osaka @Booking.com
scrapy crawl booking_score -a start_url="https://www.booking.com/searchresults.ja.html?city=-240905;ss=%E5%A4%A7%E9%98%AA%E5%B8%82" -o osaka180609score_bk.csv