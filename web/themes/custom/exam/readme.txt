$black: #373737;
$blue: #4c84be;
$gray: #828282;
$white: #fff;
$gutter: 30px;
$gutterM: 20px;
$gutterS: 10px;
font-size: 18px;
font-weight: 400;
font-family: 'Roboto', sans-serif;
h1 > 40px (dsk) 25px (mb do dsk);
h2 > 32px;
h3 > 25px;
h4 > 20px;
Font-link:
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"


/* For screens with width less than 320px*/
@media (max-width: 320px){
     /* CSS rules for responsive design */

   }
/* For screens with width from 320px to 768px */
@media (min-width: 320px) and (max-width: 768px) {
   /* CSS rules for responsive design */
}

/* For screens with width from 768px to 1024px */
@media (min-width: 768px) and (max-width: 1024px) {
   /* CSS rules for responsive design */
}

/* For screens with a width of more than 1024px */
@media (min-width: 1024px) {
   /* CSS rules for responsive design */
}

*******************************************************************************************

/* For screens with width less than 500px*/
@media (max-width: 500px){
  /* CSS rules for responsive design */

}
/* For screens with width from 501px to 800px */
@media (min-width: 501px) and (max-width: 800px) {
  /* CSS rules for responsive design */

}
/* For screens with width from 801px to 1200px */
@media (min-width: 801px) and (max-width: 1200px) {
  /* CSS rules for responsive design */
}

.primary-nav__menu-link-inner:after {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 0;
    content: "";
    transition: transform 0.2s;
    transform: scaleX(0);
    transform-origin: left;
    border-top: solid 5px #2494db;
}

# Drupal specific
/web/core/
/web/modules/contrib/
/web/themes/contrib/
/web/profiles/contrib/
/web/libraries/
/web/sites/*/files/
/.docksal

# Ignore development specific files
/sites/*/settings/settings.local.php
/sites/*/services.yml

# Ignore compiled PHP files
*.phpc

# Ignore IDE specific files
.idea/
.vscode/

# Ignore configuration export files
/config/default/
/config/sync/
/config/optional/

# Ignore files generated during installation
/sites/*/settings.php
/sites/*/settings.local.php

# Ignore private files directory
/sites/*/private/

# Ignore backup files
*.bak
*.swp
*~
*.orig
*.old
