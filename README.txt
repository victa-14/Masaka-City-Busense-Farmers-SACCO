MASAKA CITY BUSENSE FARMERS SACCO - WEBSITE PACKAGE

Open index.html in a browser, or upload this whole folder to your web host.

IMAGES
Put image files in the images folder using these exact names (JPG, about 1200 px wide):
  images/logo.jpg, images/group.jpg, images/board.jpg
  images/news-1.jpg, images/news-2.jpg, images/news-3.jpg (optional; a card with no file shows without a photo)
To use a different file name, open index.html and change the src="images/..." link.

NUMBER OF MEMBERS AND REVIEWS
Near the bottom of index.html, find:  var MEMBERS=null,REVIEWS=[];
  Set MEMBERS to your number, for example  var MEMBERS=250;  and the count appears and counts up.
  Add reviews like this:  REVIEWS=[{name:"Member name",stars:5,text:"Their review."}];
  The average rating and review count update on their own.

OPENING HOURS
Search index.html for "9:00 am to 4:00 pm" to change them.
