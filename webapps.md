# Web Apps Tips
## Prologue
This has been created as per request by the main administrator of Pinoy IT Geeks. Since It'll be catalogued properly if archived.

## Submission and Queries
1. You may Add your own tips by sending me a pull request
2. You may submit an issue about the tips given here
3. You may PM me regading the tips given here

## License and Issues
1. You may copy-paste this in your own blog as long as you give full reference to PITG and this markdown
2. You may never profit or share from the information of others. (Information is freedom)

##Tips

###ProTip I
Its imperative that you as a developer should know "The Back End" from the "Front End".

PHP (does the logic, gets data from DB, does awesome shit)
HTML (front end, what the users see)

Do not mix them up..

###ProTip II
1. Bandwidth Allocation
⋅⋅⋅Cart Systems, Web Applications and Web Systems (including social media, or privately run web apps) are resource hogs. This means that they eat alot of resources and CPU RAM eaters thats why Bandwidth allocation goes to its limit BUT this is only applicable with "Shared Hosting" since alot of domains are using thesame resources and would shut down the server if not properly fixed. 
⋅⋅⋅So, you may either use AWS (Amazon Web Services), VPS (Virtual Private Servers e.g. Digital Ocean) or Private Cloud Repositories (PagodaBox, Heroku, AppFrog or Create your own).
⋅⋅⋅You have to assume that your userbase shall have a minimum of 50,000 users at the same time. And Per User Experience Design convention, your bouncerate should be 2 seconds or less (Page load).
⋅⋅⋅To remove the nuisance of Bandwidth allocation, the use of Virtual Private Servers, Clouds or AWS itself would give you SOLE capability of bandwidth allocation. This means that you can extend it to make it "unlimited" via the following:

⋅⋅1. use CDNs (Content Delivery Networks) try rightclicking on any facebook image, you'll notice that it uses "akaiama-cdn" its facebook's sole CDN. it reverts traffic from the main server to the CDN server for less server load
⋅⋅2. use Cloudflare protection: Some websites are DDOSes themselves accidentally due to wrong programming or due to alot of server load.
3. Replicate your Database


2. Databases Storages
⋅⋅⋅Web Apps should ALWAYS have the capability to be fast on runtime, and using MySQL ONLY would make the site take longer to load. Use hybrids (its what facebook, twitter, and other resource hogs uses)
use CouchDB + MySQL or Reddis + MySQL or etc etc.


###ProTip III
####Setting Up a STACK
first off here's what a stack is (Stackoverflow Resource)[http://stackoverflow.com/questions/382665/what-is-meant-by-the-term-web-stack]

1. In Windows
---Windows STACK is called WAMPP or XAMPP. You usally heard this as a whole big installer. Well, they're not, they're one big giant package for installation of packages. WAMPP (Windows, Apache, MySQL, PHP, Perl), XAMPP (Cross Apache, Windows, MySQL, PHP, Perl). 
---I'd rather (as a developer, and a student) to use a pre-existing build of the packages thru the installers. But, take note that not all of the required libraries or installers are autoloaded on the `PATH`. And rather
---Use (XAMPP)[https://www.apachefriends.org/download.html]
⋅⋅1. After installation you should
⋅⋅⋅1. go to /xampp/php/bin and autoload them to your `$PATH` this could easily be googe-lable.
⋅⋅⋅2. check your php configuration if its working type in `php -v` on your command line interface
---These is required since alot of development procedures on different frameworks are already being used by frameworks and developers. Alot of frameworks like `laravel`, `Fuel` and `Zend` uses different procedures on the CLI.

