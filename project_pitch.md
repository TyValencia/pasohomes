Ty Valencia
Professor Dahilig, CMSI3801, Languages and Automata I

## Project Pitch

**Project Overview:**

I will be making a website for Paso Homes, a business start-up in Dr. D'Mello's business incubator course. Paso Homes is a 100% online platform where customers can rent living spaces by the month. The website will contain data from homeowners that the customers can look up and connect with. It will be written in Javascript and HTML. It will use APIs such as Firebase for storing data, Google Maps for displaying the locations of homes for rent, and Twilio for SMS integration. 

Notes: 
- A friend of a friend is in ENTR4380 and was looking for a coder for their startup. I am not in that course, but I decided to help so that I could get more experience.

**Feature Specification:**

* Landing page
	- Header buttons 
		- Sign in / sign up
		- I am a homeowner
	- CTA for users to sign up
	- Browse current homes
		- Page-wide map
	- Footer
		- FAQ
		- Contact us
		- Privacy policy 
		- Send us feedback
* Browse homes page
	- Google Maps API
* Database creation 
	- Firebase
* Matching criteria
	- Code that checks the database for matches based on what the user enters
	- Send the user an email/text when a match is found
* Account management 
	- Sign in with Google account API
	- Email management with MailChimp
		- Integrate both together to add new sign-ups to the list automatically
	- Text management with Twilio
		- Text a user when a match is found
* Feedback
	- Google form
	- Included in emails

**Future features** 

* Analytics 
	- Google Analytics
	- Use tracking code to get user behavior, sign-ups, and other metrics
* Security
	- Make landing page HTTPS-secured 
	- Encrypt user data in Firebase
* Chatbot
	- GPT API


**Technical Specification:** 

Coding languages: Javascript, HTML, CSS

APIs: Google Maps, Google Sign-in, Firebase, MailChimp, Twilio

What they want their website to be like: <br> 
	- https://www.spotahome.com/ <br> 
	- https://nomadremote.vercel.app/
