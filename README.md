# Only Scraping Hotel's Data @TripAdvisor.jp, Booking.com

Python Function To Scrape Hotel's data is hotel's name, address, review text, score, and so on, "Except pricing data"

Based on 'https://github.com/monkeylearn/hotel-review-analysis'

Special thanks to @monkeylearn

## crawl to review-text of hotels in kyoto @TripAdvisor.jp
scrapy crawl tripadvisor_review -a start_url='https://www.tripadvisor.jp/Hotels-g298564-Kyoto_Kyoto_Prefecture_Kinki-Hotels.html' -o filename.csv

## crawl to review-score of hotels in kyoto @TripAdvisor.jp
scrapy crawl tripadvisor_score -a start_url='https://www.tripadvisor.jp/Hotels-g298564-Kyoto_Kyoto_Prefecture_Kinki-Hotels.html' -o filename.csv

Thank you for @monkeylearn!!
## crawl to review-text of hotels in osaka @Booking.com
scrapy crawl booking_review -a start_url='https://www.booking.com/searchresults.ja.html?city=-240905;ss=%E5%A4%A7%E9%98%AA%E5%B8%82' -o filename.csv


## crawl to review-score of hotels in osaka @Booking.com
scrapy crawl booking_score -a start_url='https://www.booking.com/searchresults.ja.html?city=-240905;ss=%E5%A4%A7%E9%98%AA%E5%B8%82' -o filename.csv


As you know, I'm Python Beginner.
I'm glad you to give feedback.

"Hi gkzz,
Sorry for editing your file without permision.
I am a student and doing a science research at school.
But I have some troubles when I trying to crawl booking.com's data.
I really want to have your contact like email or something like that because I want to discuss and leanrn more from you about crawling data.
My email is giangttc41@due.edu.vn
Looking forward to hearing from you.
Have a nice day,

Chau Giang Tran"
