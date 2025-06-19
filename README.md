# WordPressLinksReplace
**Problem**: During my work at Deakin, we had a ticket come in asking us to update ~300 links on their WordPress site. There wasn't a singular change to the front of the URLs so we couldn't just do a single search and replace in the database to update the links. For context, this is a subsite on our larger multisite WordPress instance.

**Solution**: The site owners had an Excel file with all the old URLs along with their new replacements. I decided to pull out all those links from the Excel file with Python + Pandas and generate a list of SQL queries to run on the database.

**Why this project?**
- While our internal WordPress support rules specify that all site content updates must be done by the site owners (our team just looks after the initial subsite creation and any critical bugs), I had the time to write this script in order to save this team updating these links one by one with a plugin such as Better Search Replace.
- I get to refresh my knowledge of Python and Pandas and demonstrate my ability to quickly jump to other languages I don't often work in.
- I get to demonstrate some of my knowledge of building SQL queries.
- I get to demonstrate one way I tackle a seemingly burdensome/mundane task with a more efficient and elegant solution.
