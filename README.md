# ConnectCircle

## Goal for this Project

Welcome to ConnectCircle, this is a meeting app for everybody who want to meet virtually. It has a simple interface and easy to use. It allows users to create a meeting and invite other users to join the meeting. The application is accessible from various platforms like web, mobile and desktop.
To use the application, you need to register an account. Users are encouraged to pay for subscription plan to be able to create a meeting by themselves. The subscription plan's price depends on how many users are going to join the meeting.

[Live Project Here]()

---

## Table of Contents

## User Experience - UX

The website is created to be accessible to all users. The website is designed to be easy to use and intuitive. The navigation is simple to understand and easy to use. The background of the app is consistent with the design and aimed at keeping the user's attention on the app.

---

## User Stories

#### First time visitor

- As a first time visitor, I want to be able to see an informative page about the application, so that I can understand what's about.
- As a first time visitor, I want to be able to see a list of all pricing plans, so that I can choose one.
- As a first time visitor, I want to be able to easily navigate through the application, so that I can find what I am looking for.
- As a first time visitor, I want to be able to register, so that I can have an account.
- As a first time visitor, I want to be able to login, so that I can access my account.

---

#### Registered user

- As a registered user, I want to be able to see my account informations, so that I can update my informations.
- As a registered user, I want to be able to see my payment history, so that I can see what I have paid for.
- As a registered user, I want to be able to see what type of plan I have, so that I can find out what features are available.
- As a registered user, I want to be able to see when my plan will expire, so that I can know when I need to renew.
- As a registered user, I want to be able to create meetings, so that I can invite other users to join me.
- As a registered user, I want to be able to set up a password for a meeting, so only people I invite can join.
- As a registered user, I want to be able to join a meeting I have been invited to, so that I can join the meeting.
- As a registered user, I want to be able to leave a meeting, so that I can leave the meeting.
- As a registered user, I want to be able to change settings, so that I can change camera and microphone settings.
- As a registered user, I want to be able to change my password, so that I can protect my account.
- As a registered user, I want to be able to logout, so that I can logout of my account.
- As a registered user, I want to be able to turn on/off my microphone, so that other users can or cannot hear me.
- As a registered user, I want to be able to turn on/off my camera, so that other users can or cannot see me.
- As a registered user, I want to be able to control microphones of other users, so that I can control them in a meeting I created.

---

## Agile Methodology

All functionality and development of this project were managed using GitHub which Projects can be found
[here](https://github.com/JureSesel/connect-circle/issues)
## Design

The idea of the design was taken from [Prime React](https://www.primefaces.org/primereact/). It helped to create clean and attractive design. The simplicity of the design was also taken into consideration as it was a main goal to keep users' attention on the functionality of the application.

### Color Palette

### Typography

The typography was designed to be readable and easy to use.

Font-family: Roboto, Helvetica Neue Light, sans-serif;

This font-families are coming from Prime React.

### Images

The is only one image that was used in the application to make the landing page more eye-catching.

![Home page Hero image]()

This image was taken from []().

### Wireframes

Wireframes for this project can be located [ here ](documentation/design/ConnectCircle_wireframes.pdf)

---

## Business Model

The Business Model is B2C, meaning that the company sells products (subscriptions) to customers only.
It's only focused in the individual transactions at the moment.

### Target Customers

ConnectCircle potential customers is the people who want to meet virtually. It includes friends who simply want to meet, colleges who are living in remote areas and have to discuss some urgent matters, and even students who wants to organize a study group. It excludes people who are younger than 13 years old.

### Strategy Plan

The strategy trade-off plan is to make the application as user friendly as possible.

- Simple interface.
- Easy to use.
- Intuitive navigation.
- Consistent design.
- Accessible to all users.
- Free access to all users in the world to join the meeting.
- Low cost of the subscription plan.
- Security of the application.
- Tech support.

---

## Web Marketing

* Facebook

Having a page on facebook is a great way to get people to join the meeting on ConnectCircle. Facebook has millions of users and is a great way to get people to become members of ConnectCircle community, it may easily lure new customers and increase the number of members who are purchasing the subscription plans.

* Newsletter

The newsletter subscription is a great way to deliver the latest news and updates to the users and subscribers.

---

# Features
​
### NavBar
​
There are 2 types of the navbar:
​
* Navbar for logged out users:
​
![NavBar]()
​
  - "Home" button: takes the user to the home page.
  - "Pricing" button: takes the user to the pricing page.
  - "Contact" button: takes the user to the contact form page.
  - "Login" button: takes the user to the login page.
  - "Register" button: takes the user to the register page.

* Navbar for logged in users:
​
![NavBar]()
​
  - It has a profile button. If user clicks this button, the user will see a sidebar with the user's profile information:
​
![SideBar]()
​
    It also has 3 buttons:
​
    - "Home" button: takes the user to the home page.
    - "Profile" button: takes the user to the profile page.
    - "Settings" button: takes the user to the settings page.
​
  **Note:** If user bought a subscription, there will be an additional button "Create Meeting" in the sidebar.
​
![SideBar]()
​
  - "Home" button: takes the user to the User's home page. If user is already on the his/her home page, the button will not be displayed.
​
![Home Button]()
​
  - "Logout" button: logs the user out.

### Home Page

![Home page]()

This is the home page of the website. It has the description of the website and focus on potential customers to join the community.

It includes the following features:

* Hero Section :

![Hero Section]()

It has a content on the left side and a background image on the right side.

It includes the call to action: "Absolutely new level of cloud meetings. Our platform is the best way to manage your meetings and video calls.". It also has 2 buttons:

- "Learn More" button: takes the user to the benefits section of the home page;
- "Get Started" button: takes the user to the register page.

* Benefits Section :

![Benefits Section]()

This section describes the benefits of choosing this platform over other platforms.

  - Built for Everyone.
  - End-to-End Encryption.
  - Easy to use.
  - Fast & Global support.
  - Open source.
  - Trusted security.

* Get Started Section :

![Get started section]()

This section has a call to action to get people to join ConnectCircle community and a buttons:

  - "See pricing" button: takes the user to the pricing page;

### Pricing Page

**When the user is logged out.**

![Pricing Page]()

It has the same navbar and footer as a Home page.

It has a title and 3 pricing plans' cards, which include full information about the plans and a "Buy Now" button.

* Basic Plan :

![Basic Plan]()

* Premium Plan :

![Premium Plan]()

* Enterprise Plan :

![Enterprise Plan]()

If the user is not logged in, the user will see a alert message to register/login first.

Under the pricing cards there is a call to action to get people to join ConnectCircle community and a buttons:

![Get started section]()

**When the user is logged in:**

![Pricing Page]()

When the user clicks "Buy Now" button, the user is taken to the payment page.

### Footer
​
![Footer]()
​
It has a logo, email, phone number. It also has the following links:
​
- "Contact" button: takes the user to the contact form page.
- "Terms of use" button: takes the user to the terms of use page.
- "Privacy policy" button: takes the user to the privacy policy page.
- "Newsletter" button: opens modal form with the newsletter form.
​
![Newsletter]()
​
  - If the user has already subscribed to the newsletter, the "Newsletter" form will show an error message.
​
![Newsletter]()
​
  - When the user subscribes to the newsletter, the user will receive an email with a confirmation message.
​
![Newsletter]()
​
  - If user clicks " unsubscribe" link in thee email, the user will be unsubscribed from the newsletter
​
![Newsletter]() 
​
- Social media icons (Facebook, Twitter, Instagram, LinkedIn): takes the user to the social media pages.

### Payment Page

![Payment Page]()

Payment page is generated by the Stripe Checkout API. Here the user can enter his/her contact and credit card informations. The use of Stripe Checkout makes it easy for the user to pay for the subscription and proofs that only Stripe gets the credit card information and not my website. 

After successful payment, the user is taken to the Home page.

#### Successful payment emails

After successful payment, the user is taken to the Home page. User will see the message notifying him/her that the payment was successful.

User will also receive an email with the created subscription.

![Successful subscription creation]()

And the following email will be also sent to the user about the payment:

![Successful payment page]()

The money will be payed to the Dr.Meeting account automatically each month and the user will will be sent the same email each month till the user cancels the subscription.

User can also download the invoice for the payment.

[Successful payment invoice]()

If the payment is not successful, the user will receive an email with the error message and the link to the stripe customer portal.

![Failed payment page]()

### User Dashboard

![User Dashboard]()

It has 4 cards:

* Profile card :

![Profile card]()

This card has a User name, User email, and a button "Profile page". If the user clicks this button, the user will be redirected to the profile page.

* Pricing card :

![Pricing card]()

It has subscription plan and the description of functionality according to the plan.

It also has a button "See pricing" that takes the user to the pricing page.

If user has purchased a subscription plan, this card will look different.

![Pricing card]()

If user clicks "See subscription" button, the user will be redirected to the subscription page.

* Settings card :

![Settings card]()

It has a data on the current camera and microphone settings. There is a button "Settings" that takes the user to the settings page.

* Meetings card :

![Meetings card]()

It has short description of the meeting's card and 2 buttons:

  - "Create meeting" button: takes the user to the create meeting page. *This button is disabled if the user is using free plan.*
  - "Join meeting" button: takes the user to the join meeting page. When the user clicks this button, the user will see a modal window with an input field to enter the meeting's token:

![Join meeting modal]()

If the user enters a valid token, the user will be redirected to the meeting page.

If the user has purchased a subscription plan, this card will look differently:

![Meetings card]()

  When the user clicks "Create Meeting" button, user will be redirected to Create meeting page.

### Create Meeting Page

![Create meeting page]()

If user bought enterprise plan, this page will have all 3 options for Max guests.

If user bought premium plan, this page will have only 2 options for Max guests (11 guests buttons will be disabled).

If user bought basic plan, this page will have only 1 option for Max guests ( 8 and 9 guests buttons will be disabled).

![Create meeting page]()

If the user without a subscription plan comes to this page by directly typing the URL, the page will be redirected to the home page and an alert message will be shown.

### Edit Profile Page

![Edit Profile page]()

This page has a form to edit the user's profile. The user can edit his first name, last name, birthday, country, password, and avatar. After clicking "Save" button, the user will be redirected to the user dashboard.

### Settings Page

![Settings page]()

This page allows user to set the camera and microphone settings.

When user click on camera, the user will see a selected options:

![Settings page]()

When the camera is selected, the user will see a preview of the camera.

![Settings page]()

![Settings page]()

When user click on microphone, the user will see a selected options:

![Settings page]()

When the microphone is selected, the user will see a knob that shows the volume of the microphone.

![Settings page]()

When user click "Save" button, the settings will be saved.

As it's shown in the screenshots, the user will be able to see chosen camera and microphone in different color:

![Settings page]()

### Subscription Page

![Subscription page]()

This page has a data on the current subscription plan and provides data on the future payments.

It has 3 buttons:

- History button: opens a modal window with the history of the payments.

![History modal]()

- Portal button: stripe customer portal for the user to manage his payments.

- Cancel button: to cancel subscription.

![Cancel modal]()

When the order is cancelled, the user will receive an email with a confirmation message and the money will be refunded.

![Cancel email]()

### Register Page

![Register Page]()

This page has the following fields:

- First name.
- Last name
- Email.
- Password
- Confirm password.
- Birthday.
- Country.

It has a checkbox in order to confirm that the user agreed to the terms and a register button;

If user has already created account before, he/she can use "Already have an account? Login" link to redirect to Login page.

When the user registers, the user will receive an email with a confirmation message.

![Register modal]()


### Login Page

![Login Page]()

This form has 2 fields:

- User email.
- Password.

Login button and a link to register page and forgot password page. When user clicks "Register" link, he or she will be redirected to Register page. If user clicks "Forgot Password", he or she will be redirected to forgot password page.

When the user attempts to change the password, the user will receive an alert email to warn him/her about the security:

![Forgot password email]()

### Contact Form Page

![Contact Form Page]()
This page has a form to contact the support.

For the logged in user, the fields will be prefilled with the user's data.

![Contact Form Page]()

After successfully submitting the form, the user will get an email with a confirmation message.

![Contact form page]()

### Alert Messages

To notify user about the result of the action, the system will display an alert messages in the right top corner of each page.

  - Success: the action was successful.

![Success alert]()

  - Error: the action was not successful.

![Error alert]()

--- 

### Meeting Page

![Meeting page]()

![Meeting page]()

![Meeting page]()

![Meeting page]()

![Meeting page]()

- If the user is the host, the navigation bar will look like this:

![Meeting page]()

It will have the following buttons:

1. Copy room token button: copies the room token to the clipboard.

![Copy room token button]()

2. Camera button: toggles the camera on/off.

![Camera button]()

![Camera button]()

3. Microphone button: toggles the microphone on/off.

![Microphone button]()

4. Mute all controls button: toggles the mute all controls on/off.

![Mute all controls button]()

![Mute all controls button]()

5. End meeting button: ends the meeting.

![End meeting button]()

6. Fullscreen button: toggles the full screen on/ off.

![Fullscreen button]()

- If the user is not the host, the navigation bar will look like this:

![Meeting page]()

It will have the following buttons:

* Camera button: toggles the camera on/off.
* Microphone button: toggles the microphone on/off.
* Leave meeting button: leaves the meeting.

![Leave meeting button]()

* Fullscreen button: toggles the full screen on/off.

--- 
### GitHub Project Management

![GitHub Project Management]()

GitHub Project Management was used as the main method to manage the project. It was used to control the project's workflow and to track the project's progress. The project was created using [GitHub](www.github.com).

I used set the projects according to the application's functionality and set up issues for each feature to keep control of the development.

![GitHub Project Management]()

![Tasks]()

---

## Information Architecture

### Database

* The database was created using PostgreSQL.

### Entity-Relationship Diagram


![ERD]()


### Data Modeling


#### UserToken Model
| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| user_id       | user_id       | IntegerField  |           |
| token         | token         | CharField     | max-length=255 |
| created_at    | created_at    | DateTimeField |           |
| expired_at    | expired_at    | DateTimeField |           |

#### ForgotPasswordToken Model
| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| Email         | email         | EmailField    |           |
| token         | token         | CharField     | max-length=255 |

#### User Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| avatar        | avatar        | CloudinaryField |   folder='cloud_meetings_avatars', null=True, blank=True,        |
| email         | email         | EmailField    | unique=True, max_length=254 |
| Username      | username      | None     |  |
| first_name    | first_name    | CharField     | max_length=50 |
| last_name     | last_name     | CharField     | max_length=50 |
| birth_date    | birth_date    | DateField     |   |
| country       | country       | CharField     | max_length=100 |
| camera_id     | camera_id     | CharField     | max_length=100, null=True, blank=True |
| microphone_id | microphone_id | CharField     | max_length=100, null=True, blank=True |

#### SubscriptionPlan Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| name          | name          | CharField     | max_length=255 |
| price         | price         | DecimalField  | max_digits=10, decimal_places=2 |
| description   | description   | TextField     |           |
| created_at    | created_at    | DateTimeField |           |
| updated_at    | updated_at    | DateTimeField |           |
| guest_limit   | guest_limit   | IntegerField  | defualt=0 |
| can_create_rooms | can_create_rooms | BooleanField | default=False |
| stripe_plan_id | stripe_plan_id | CharField     | max_length=255, blank=True, null=True |

#### Membership Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| user          | user          | OneToOneField |   User, on_delete=models.CASCADE, related_name='membership'        |
| is_active     | is_active     | BooleanField  | default=True |
| type          | type          | ForeignKey    | SubscriptionPlan, on_delete=models.CASCADE, related_name='memberships'        |
| default     | default     | SubscriptionPlan.objects.get(name='Free').id) |           |
| opened_at     | opened_at     | DateTimeField |           |
| renewed_at    | renewed_at    | DateTimeField |           |
| expires_at    | expires_at    | DateTimeField |  null=True, blank=True         |
| stripe_id     | stripe_id     | CharField     | max_length=255, blank=True, null=True |

#### Payment Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| membership    | membership    | ForeignKey    | Membership, on_delete=models.CASCADE, related_name='payments'        |
| created_at    | created_at    | DateTimeField |           |
| amount        | amount        | DecimalField  | max_digits=10, decimal_places=2, blank=True, null=True |

#### PaymentHistory Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| user          | user          | ForeignKey    | User, on_delete=models.CASCADE, related_name='payment_history'        |
| payments      | payments      | ManyToManyField | Payment, related_name='payment_history'        |

#### ContactUs Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| name          | name          | CharField     | max_length=100 |
| email         | email         | EmailField    |  |
| subject       | subject       | CharField     | max_length=100 |
| message       | message       | TextField     |           |

#### NewsletterSubscription Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| email         | email         | EmailField    |  |

#### VideoRoom Model

| Name          | Database Key  | Field Type    | Validation |
| ------------- | ------------- | ------------- | ---------- |
| token         | token         | CharField     | max_length=32, default=create_room_token |
| host          | host          | OneToOneField |   User, on_delete=models.CASCADE, related_name='hosting_room'        |
| max_guests    | max_guests    | IntegerField  | default=3 |
| guests        | guests        | ManyToManyField | User, related_name='current_rooms', blank=True |
| screen_sharing_enabled | screen_sharing_enabled | BooleanField | default=False |
| presentation_enabled | presentation_enabled | BooleanField | default=False |
| chat_enabled | chat_enabled | BooleanField | default=False |
| protected | protected | BooleanField | default=False |
| guests_input_control | guests_input_control | BooleanField | default=False |
| password | password | CharField | max_length=32, default='', blank=True, null=True |
| guests_muted | guests_muted | BooleanField | default=False |

---