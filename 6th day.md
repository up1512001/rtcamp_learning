# got to know about sourse ~/.zshrc for reloading zshrc file after change
# bulk mail sending Amazon SES or SendGrid 
# if inside cd3 and need to go inside cd1 then use cd ../cd1
# got to explore php dependency injection in which we pass dependency as construct perameter

## php dependency injection
`<?php
   class Profile {
      private $language;
      public function setLanguage($language){
         $this->language = $language;
      }
   }
   $profile = new Profile();
   $language = array["Hindi","English","Gujarati"];
   $profile->setLanguage($language);
?>
Here Language array passed as dependency 
`