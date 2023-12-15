
**Problem Statement**:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

There are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating, etc. ) in order to get a higher lead conversion.

X Education wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score h have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

**Solution**
Lead_Source_Reference and Others (Coefficient: 2.6087)
current_occupation_Working Professional (Coefficient: 1.2053)
Time_on_Web (Coefficient: 1.0047)
Lead_Source_Olark Chat (Coefficient: 0.5527)
Lead_Source_Google (Coefficient: 0.3433)
Page_Views_Per_Visit (Coefficient: -0.2062)
Do_Not_Email (Coefficient: -1.0616)
Lead_Source_Organic Search (Coefficient: 0.2989)
Lead_Source_Google (Coefficient: 0.3433)
Specialization_Management Specializations (Coefficient: -0.0611)
Total_Visits (Coefficient: 0.1000)
Lead_Origin_Landing Page Submission (Coefficient: 0.0291)
City_Non-Maharashtra Cities (Coefficient: -0.0356)
City_Non-Mumbai Maharashtra Cities (Coefficient: 0.0810)

Are the to nine variables in my model which contribute most towards the probability of a lead getting converted.
