# Predict-first-travel-booking-Classification-problem-
Prediction of first booking by a new user at Airbnb 

#### Problem Statement

By accurately predicting where a new user will book their first travel experience, Airbnb can share more personalized content with their community, decrease the average time to first booking, and better forecast demand.

#### Dataset Description :

The data Set has 213451 examples and 15 features + the target variable (country_destination). 2 of the features are ints, 1 is float and 13 are objects.

##### Below, I have listed the features with a short description:

id: User id

date_account_created: The date of account creation

timestamp_first_active: The timestamp of the first activity, note that it can be earlier than date_account_created or date_first_booking because a user can search before signing up

date_first_booking: The date of first booking

gender: The gender of customer

age: The age of customer

signup_method: The signup process used by the customr. viz Website login, Google login, Facebook login

signup_flow: The page a user came to signup up from

language: The international language preference

affiliate_channel: What kind of paid marketing

affiliate_provider: Where the marketing is e.g. google, craigslist, other

first_affiliate_tracked: Whats the first marketing the user interacted with before the signing up

signup_app: The app for signup viz iOs, Android etc.

first_device_type: The type of device used by customer viz.Windows/Mac Desktop, Iphone, Ipad, Android Phone/Tablet

first_browser: The browser used by customer

country_destination: This is the target variable to be predicted
