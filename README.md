# grstartups
A basic code walkthrough of GR Startups — for anyone looking to see code, please email Ben Parsell. All code is proprietary at this time, but can certainly be seen for anything professional or educational.

https://grstartups.com is a platform, written in PHP and based on the Laravel Framework, that provides a hub for entrepreneurship in Grand Rapids, MI. The platform, as of Oct. 2017, has scaffolding for "Spotlights", or entrepreneur interviews and stories to be added, as well as "Resources", or entrepreneurship resources (think co-working spaces, accelerators, legal, etc).

## GR Startups Frontend
The GR Startups frontend, built on Bootstrap, shows off all of the models created in the backend, including Spotlights, Resources, and general news pieces. Once something is created in the CMS backend, it is automatically created into the database, and viewed on the frontend.

## GR Startups Backend
In update 2.0 (set to release in Nov. 2017), a full-scale administrative backend was added to act as a CMS with roles and permissions. The idea behind this, was to create a self-sufficient paltform, where an account can be generated, and one of the local "resources" can fill in their information using a form, choose a template designed by Inveigle, and auto-generate a frontend page upon submission — all while having a restricted account becasue of roles and permissions

## Spotlights
Spotlights are a model (Laravel as an MVC framework) where each one holds information from an entrepreneur interview. With the help of a few other individuals, we'll be producing some video interviews, and each spotlight will have its own dedicated page, where the backend would create or POST those to be viewable on the frontend. 

## Resources

## News

## Roles & Permissions
GR Startups is controlled by roles and permissions on the backend, to prevent any data being accessed or altered in an inappropriate way, while also giving way to a self-sufficient backend where people outside from GR Startups, or Inveigle, can actually add information and edit the information they're responsible for. The frontend portion is open for anyone to view. 

## Scalability
Beyond Grand Rapids, this platform can be implemented across just about any community. It takes some community involvement to populate a database for this, but is overall low maintainence and provides an excellent resource for the business and professional community there.
