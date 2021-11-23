# KHKB
Kunsthallekleinbasel Generalüberholung der bisherigen Webseite

How I made it run on Ubuntu:

1. Create folder in Documents and name it sth memorable (KHKB)
2. Create new repo on GitHub.com, call it sth memorable (KHKB), give it a good description, decide if you want it public or private and dont add anything into it so the website gives you perfect instructions on what to do in case i get sth wrong here or there are changes in the future. If you follow those instructions, you can skip steps 3-4. If you dont intend on doing what i did to make your own version of it, but to just check my stuff out, instead just clone the repo as seen in step 3 and skip this step.
3. Open terminal in your folder that you created earlier and run (or use your own link if you intend on doing your own thing instead of an exact copy): $ git clone https://github.com/ghetterking/KHKB.git
4. Check if everything went fine by running $ git status
5. If you have cloned my entire repo, jump to step 7. otherwise, download or create your own docker-compose.yml file which will enable you to install and run wordpress, then put it into the folder you created and named last.
6. To double check if you put it into the right folder and did the git setup correctly, add, commit and push as usual and check on the website. If it's right there and not in some folder you may have created superfluously, you did well.
7. Open terminal in the folder that docker-compose.yml is located in (as seen in my repo) and run $ docker-compose up -d
8. Now open localhost:8080 (troubleshoot this in OBSTACLES.md file at point 5.), this should bring you to the installation screen of wordpress and allow you to create your own login for wordpress after having entered the correct data that you can find in docker-compose.yml, or if you want to edit my site use "KHKB" as both your login data.
9. Update, maybe download necessary themes and plugins, finally click visit site when hovering over the house symbol to check out my site if that's what you're here for.
10. Some themes and plugins i've used: Blocksy, Astra, Elementor Website Builder, Starter Templates, Smooth Back to Top Button, Startinger, Ajax Search Lite, Mappress Maps for Wordpress, Multiple Themes, Visual Portfolio Posts & Image Gallery, WP Dark Mode, Woocommerce and "akismet antispam", but i specifically delete the pre-installed "Hello Dolly" usually.
11. Trello (work process): https://trello.com/b/pnBGwZjP/khkb
have fun, go crazy

PS: I have also uploaded the entire thing as a zip file just to make sure wordpress doesnt forbid some parts from being uploaded.