# Flipkart_scrap_Laptops_Price
Flipkart_Apple Laptops_Price

Link: https://www.flipkart.com/laptops/pr?sid=6bo%2Cb5g&fm=neo%2Fmerchandising&iid=M_8b3b3f65-7ceb-4375-912c-d2bcdde87c58_1_372UD5BXDFYS_MC.34WHNYFH5V2Y&otracker1=hp_rich_navigation_PINNED_neo%2Fmerchandising_NA_NAV_EXPANDABLE_navigationCard_cc_13_L1_view-all&cid=34WHNYFH5V2Y&p%5B%5D=facets.brand%255B%255D%3DAPPLE&otracker=clp_metro_expandable_6_26.metroExpandable.METRO_EXPANDABLE_Apple_laptops-store_SKIHMOPFPDC3_wp9&fm=neo%2Fmerchandising&iid=M_b4d0e2ef-aaac-4e7e-9272-9b8be53c2dc5_26.SKIHMOPFPDC3&ppt=clp&ppn=laptops-store&ssid=j5fwd6niaz0hnchs1645514684273

Procedure

Step1.Import necessary library

Step2.The Url of the website to be scraped to be imported into the jupyter file

Step3.Change the current directory on the install path of webdriver.

select geckodriver-v0.30.0-win64.zip file.-> used to run webbrowser on remote server

coping above file and pasting in different directory with folder -> 'script webdriver' is used to automate remotly to open -> fetch url directly from selenium.

then create new notebook and change directory in notebook to webdriver folder

open a firefox browser(using selenium webdriver) -- >

load page -->

get html

step4.page_source method is used retrieve the page source of the webpage the user is currently accessing. The main use of this method to find something in the page source like finding any data or keyword.

Step5.Beautiful Soup is powerful because our Python objects match the nested structure of the HTML document we are scraping. Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.

Step6.Using find_all() to scrape data

Step7.Using find_all() to access specific/unique div tags

Step8.Requests-> allows you to send HTTP using python coding

Step9.To do this we need to stimulate a browser using tool called -> selenium webdriver --Its a Tool used for automating web browsers to do a number of tasks. --One of such task is web-scraping to extract useful data for dynamic webpages

Step10.Steps:

Select Parent tag select children tags of which are and

table> //table columns

<tr>


    <th>

        table column name

    </th>
</tr>
//table row data
<tr>

    <td>

        all the required data

    </td>

</tr>
