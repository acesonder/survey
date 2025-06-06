chch survey 

Build me a website that uses  SQL  phpmyadmin  Php with html  css
And JavaScript 
With a mobile responsive design  
Main website talks about the survey and what’s entailed 

———————***text to put on main page of website ***—————-

Cobourg Helping Community Housing
Supporting individuals experiencing housing insecurities through compassion, understanding, and action.
Login to Continue
Share Your Voice, Shape Our Support
Your experiences matter. By completing our survey, you will help us understand your needs better and improve how we advocate and support you and others in similar situations.
Mature Content Notice:This survey contains questions about sensitive topics including mental health, substance use, trauma history, and personal experiences. We respect your privacy and treat all responses as strictly confidential: you can opt to participate anonymously—no name, date of birth, or registration details are required if you select “Anonymous” on the consent form. Feel free to skip any question you’re not comfortable answering.x
Please login or register to access the survey.
How We Help
* Referral to Emergency shelter services
* Housing support knowledge and referrals
* Connections to mental health resources
* Substance use support and harm reduction
* Food Bank assistance
* Personal identification assistance
* Employment guidance and training by referals
Ready to Begin?


Login/Register to Start Survey


————————-end of text for main homepage ———————-//


“””
once  the user selects 1 of the 3  participant consent forms and fill out the inputs(if she to how they want consent to participate 


participants can complete a survey (ALL FIELDS ARE OPTIONAL IN THE SURVEY)
And choose one of three ways to consent to do the survey and participate  

1. Consent to do survey Anonymous (pre defined anon user profile in the sql database ) - click submit - goes directly to survey 
2. Consent with First name Initial and Last name  Initial - clicks submit - goes directly to survey 
3. Consent with First name, last name and date of birth . A username will be generated and displayed (example: michael brown born may 6 1984 will have a generated username of MICBRO84. And lastly security question (drop down menu with 10 to pick from ) security answers field , password field and password confirm .- clicks submit - checks that all fields are filled out, passwords match and that generated username doesn’t exists - and if all passes the account is created and user is brought right to their dashboard.  

✅ Security practices in place:
	•	Passwords hashed with PHP’s password_hash()
	•	SQL injection prevention with prepared statements
	•	Sessions secured via regeneration and role checks
	•	Minimal data exposure in responses

Admin panel features  Live Site Statistics
Stats 
Export and improving user survey data
Database integrity check 
Participants analytics 
Maintenance 
Analytics Dashboard
Survey and smart survey creation  


***survey**(ALL FIELDS ARE OPTIONAL IN THE SURVEY)
Section 1: About You
1. Question: Age
    * Element Type: Text Input (likely type="number" or type="text")
    * Name: age
    * Options: User enters their age.
2. Question: Gender
    * Element Type: Select Dropdown or Radio Buttons
    * Name: gender
    * Options: Specific options not defined in provided files (e.g., Man, Woman, Non-binary, Prefer to self-describe).
3. Question: If "Prefer to self-describe" for Gender:
    * Element Type: Text Input
    * Name: gender_self
    * Options: User enters their self-described gender.
4. Question: Sexual Orientation
    * Element Type: Select Dropdown or Radio Buttons
    * Name: sexual_orientation
    * Options: Specific options not defined (e.g., Heterosexual, Homosexual, Bisexual, Pansexual, Asexual, Prefer to self-describe).
5. Question: If "Prefer to self-describe" for Sexual Orientation:
    * Element Type: Text Input
    * Name: sexual_orientation_self
    * Options: User enters their self-described sexual orientation.
6. Question: Ethnicity
    * Element Type: Select Dropdown or Radio Buttons
    * Name: ethnicity
    * Options: Specific options not defined (e.g., lists of ethnic backgrounds, Prefer to self-describe).
7. Question: If "Prefer to self-describe" for Ethnicity:
    * Element Type: Text Input
    * Name: ethnicity_self
    * Options: User enters their self-described ethnicity.
8. Question: Birthplace
    * Element Type: Text Input
    * Name: birthplace
    * Options: User enters their place of birth.
9. Question: Years in Cobourg
    * Element Type: Select Dropdown or Radio Buttons
    * Name: years_in_cobourg
    * Options: Specific options not defined (e.g., Less than 1 year, 1-5 years, 5-10 years, More than 10 years).
Section 2: Physical and Mental Health
1. Question: Do you identify as having a disability?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: disability
    * Options: Specific options not defined (e.g., Yes, No, Prefer not to say).
2. Question: Do you take any prescribed medications?
    * Element Type: Select Dropdown or Radio Buttons (likely Yes/No)
    * Name: medications_yn
    * Options: Yes, No.
3. Question: If yes, please list your medications:
    * Element Type: Textarea or Text Input
    * Name: medications
    * Options: User lists medications. (This field is conditionally shown/cleared based on medications_yn).
4. Question: Do you have consistent access to your medications?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: access_medications
    * Options: Specific options not defined (e.g., Yes, No, Sometimes).
5. Question: Do you have any dietary needs or restrictions (e.g., allergies, religious, vegetarian)?
    * Element Type: Textarea or Text Input
    * Name: dietary_needs
    * Options: User describes dietary needs.
6. Question: Are your dietary needs currently being met?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: dietary_met
    * Options: Specific options not defined (e.g., Yes, No, Partially).
7. Question: Do you have a family doctor?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: family_doctor
    * Options: Yes, No.
8. Question: Have you ever been diagnosed with a mental health condition?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: diagnosed_mental_health
    * Options: Yes, No, Prefer not to say.
9. Question: Do you feel you need mental health support?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: mental_health_support
    * Options: Yes, No, Not sure.
10. Question: Have you ever attempted suicide?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: attempted_suicide
    * Options: Yes, No, Prefer not to say.
11. Question: Have you ever experienced an overdose?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: experienced_overdose
    * Options: Yes, No, Prefer not to say.
Section 3: Family and Childhood 1. Question: Did you have any  siblings or step siblings growing up ? 
    * Element Type: Select Dropdown or Radio Buttons
    * Name: familu_siblings
    * Options: No Siblings, Step Siblings, 1,2,3,4,5,6, Not sure.
2 .  Question: Do you have any children of your own ?  If so, how many ? 
    * Element Type: Select Dropdown or Radio Buttons
    * Name: family_offspring
    * Options: No Children, 1,2,3,4,5,6, Other
3. Question: Is there a history of any of the following in your family? (Select all that apply)
    * Element Type: Checkboxes
    * Name: family_history (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Substance abuse, Mental health struggles, Incarceration, Homelessness).
4.  Question: Have you lost someone close to you (e.g., family, friend)?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: lost_someone
    * Options: Yes, No.
5.. Question: If yes, what was the cause? (Optional)
    * Element Type: Text Input
    * Name: lost_cause
    * Options: User enters cause of loss.
6. Question: Did you experience any of the following during your childhood? (Select all that apply)
    * Element Type: Checkboxes
    * Name: childhood_experience (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Abuse (physical, emotional, sexual), Neglect, Foster care, Parental separation/divorce, Witnessing domestic violence).
Section 4: Substance Use
1. Question: Do you currently use substances (e.g., alcohol, drugs)?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: current_substance_use
    * Options: Yes, No, Prefer not to say.
2. Question: If yes, which substances do you use? (Select all that apply)
    * Element Type: Checkboxes
    * Name: substances_used (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Alcohol, Cannabis, Opioids, Stimulants, Other).
3. Question: How often do you use substances?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: substance_use_frequency
    * Options: Specific options not defined (e.g., Daily, Weekly, Monthly, Occasionally).
4. Question: Do you feel you have an addiction?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: addiction
    * Options: Yes, No, Not sure.
5. Question: If yes, to what?
    * Element Type: Text Input or Select Dropdown
    * Name: addiction_type
    * Options: User specifies addiction or selects from a list.
6. Question: Have you ever sought treatment or rehab for substance use?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: treatment_rehab
    * Options: Yes, No.
7. Question: If yes, please describe your experience (optional):
    * Element Type: Textarea or Text Input
    * Name: treatment_experience
    * Options: User describes experience.
8. Question: Do you use harm reduction supplies (e.g., clean needles, naloxone kits)?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: harm_reduction_supplies
    * Options: Yes, No, Sometimes.
9. Question: Would you use a safe consumption site if available?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: safe_consumption_site
    * Options: Yes, No, Not sure.
Section 5: Housing and Shelter
1. Question: Do you have any pets?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: have_pets
    * Options: Yes, No.
2. Question: Where are you currently staying?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: current_stay
    * Options: Specific options not defined (e.g., Shelter bed, Couch surfing, Outdoors, Own place, Transitional housing, Other).
3. Question: If "Other" for current stay:
    * Element Type: Text Input
    * Name: current_stay_other
    * Options: User specifies other living situation.
4. Question: What do you believe are the main causes of your current housing situation? (Select all that apply)
    * Element Type: Checkboxes
    * Name: homeless_cause (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Job loss, Eviction, Family breakdown, Mental health issues, Substance use, Lack of affordable housing).
5. Question: How long have you been experiencing housing insecurity or homelessness?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: homeless_duration
    * Options: Specific options not defined (e.g., Less than 1 month, 1-6 months, 6 months - 1 year, 1-5 years, More than 5 years).
Section 6: Employment and Income
1. Question: What is your current employment status?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: employment_status
    * Options: Specific options not defined (e.g., Employed full-time, Employed part-time, Unemployed, Student, Retired, Unable to work, Other).
2. Question: If "Other" for employment status:
    * Element Type: Text Input
    * Name: employment_status_other
    * Options: User specifies other employment status.
3. Question: What is your primary source of income?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: income_source
    * Options: Specific options not defined (e.g., Employment, Social assistance (OW/ODSP), EI, Pension, No income, Other).
4. Question: If "Other" for income source:
    * Element Type: Text Input
    * Name: income_source_other
    * Options: User specifies other income source.
5. Question: What forms of identification do you have? (Select all that apply)
    * Element Type: Checkboxes
    * Name: identification (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Health card, Driver's license, Birth certificate, Passport, SIN card, Government-issued ID).
Section 7: Education and Skills
1. Question: What is your highest level of education completed?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: education_level
    * Options: Specific options not defined (e.g., Some high school, High school diploma or GED, Some college/university, College diploma, University degree, Post-graduate degree, Other).
2. Question: If "Other" for education level:
    * Element Type: Text Input
    * Name: education_level_other
    * Options: User specifies other education level.
3. Question: What skills or trades do you have?
    * Element Type: Textarea or Text Input
    * Name: skills
    * Options: User lists skills/trades.
Section 8: Community and Support
1. Question: If you have used shelters, what is working well?
    * Element Type: Textarea or Text Input
    * Name: shelter_working_well
    * Options: User provides feedback.
2. Question: If you have used shelters, what could be improved?
    * Element Type: Textarea or Text Input
    * Name: shelter_improve
    * Options: User provides feedback.
3. Question: What community supports or services have you found helpful?
    * Element Type: Textarea or Text Input
    * Name: community_supports
    * Options: User lists supports/services.
4. Question: What helps you feel stable or hopeful?
    * Element Type: Textarea or Text Input
    * Name: stable_hopeful
    * Options: User describes what helps them.
5. Question: Can you describe a typical day for you?
    * Element Type: Textarea or Text Input
    * Name: typical_day
    * Options: User describes their day.
6. Question: How do you feel the community views people experiencing homelessness?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: community_views
    * Options: Specific options not defined (e.g., With compassion, With judgment, Indifferently, Mixed, Other).
7. Question: If "Other" for community views:
    * Element Type: Text Input
    * Name: community_views_other
    * Options: User specifies other views.
Section 9: Moving Forward
1. Question: What do you need to move forward?
    * Element Type: Textarea or Text Input
    * Name: move_forward
    * Options: User describes their needs.
2. Question: What are your goals for the future?
    * Element Type: Textarea or Text Input
    * Name: future_goals
    * Options: User describes their goals.
3. Question: What kind of help or services are you looking for? (Select all that apply)
    * Element Type: Checkboxes
    * Name: help_services (submitted as an array, then imploded)
    * Options: Specific options not defined (e.g., Housing, Employment or training, Mental health support, Substance use support, Healthcare, Food assistance, Legal aid).
4. Question: Would you like to be connected with someone to discuss your situation and needs further?
    * Element Type: Select Dropdown or Radio Buttons
    * Name: want_connection
    * Options: Yes, No.
