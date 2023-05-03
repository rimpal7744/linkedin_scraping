# linkedin_scraping

install dependencies by (pip install requirement.txt)

After installing dependeecies you are ready to go.


1.sales_naviagtor_crawling.py is for extracting targets from a particular link of sales navigator

You can change a link with your on line151 and can change a output file name on 152. Run it with python3 sales_naviagtor_crawling.py.

2.getting_locations.py is used to get target comapnies by scorroling to all companies extracted by sales_navigator_crawling.py

You can change input csv file on 167 line in it and output file name in 169 line.

3.sending_requests.py is made for sending connection requests to target users.logs will be saved in file under logs folder. (logs used to restart sending requests where it stopped).

4.withdraw_requests.py is a automation of withdrawing requests which are more than 1 week old from profile.

5.sending_first_message.py checks accepted requests and send message to those tagerts which have accepted our connection requests.

data_files folder contains all data  file made by different files while automation and scrapping.

### Dont forget to place username and password in repectively fields of parameter.py file
