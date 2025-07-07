\# The Sad Bag



This is a home made bag tag system that leverages the QR Code reading and native geolocalization capabilities of the ubiquitous smart phone to create better "bag tags."  The key marker of better is the ability of the bag tag to not disclose any personal information of the bag owner until the owner decides to release it.  This prevents individuals from using bag tags to capture the personal information of the bag's owner.



The QR Code contains a link to a web page that immediately sends an email to the bag owner that the bag tag was scanned (possibly alerting them to the missing bag).  The web page requests the viewer to send the bag location, and allows them to include useful information  in the notice, to the bag owner.  But the personal information of the bag owner is not displayed by default.  When the bag owner chooses, more information can be displayed on the web page to facilitate returning the bag.



This functionality is achieved through a web page hosted on GitHub, using Google Sheets to register bag tags, and Google Apps Script Web App functionality allow information of the bag to be provided to the web page, as well as send email.





