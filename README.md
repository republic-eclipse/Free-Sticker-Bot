# Free Sticker Bot 

A scraper fetching all company emails from Seedtable and Clutch websites and sending E-Mails to the companies you want Stickers from.

🚀 Install the dependancies: `pip3 install -r requirements.txt`

In order to use sendgrid, you will need to go register with them and optain the SENDGRID_API_KEY that they provide you with. You will have to store that SENDGRID_API_KEY in a sendgrid.env file.

SendGrid API Getting Started

Before running the program, remember to export your `SENDGRID_API_KEY` in terminal.
export `SENDGRID_API_KEY='YOUR_SENDGRID_API_KEY'`

Once everything is set up, go into the scrapers folder and run either python clutchco_scraper.py or python seedtable_scraper.py. This will create your csv file with all the emails.

Once that is done, go into the main directory, make sure you alter the message ur sending with your sender email, the subject line and the message content. After, just run python send_emails.py and you should be good!

💜 Happy Sending!

![Image](https://media1.tenor.com/images/0d40aa9cdeb1c567a9cfcc5315817296/tenor.gif?itemid=15228957)
