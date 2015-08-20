# Fichiers à observer :

* https://github.com/Bahanix/ocr-rails-5/blob/master/app/models/book.rb
* https://github.com/Bahanix/ocr-rails-5/blob/master/config/routes.rb#L2
* https://github.com/Bahanix/ocr-rails-5/blob/master/app/controllers/books_controller.rb
* https://github.com/Bahanix/ocr-rails-5/blob/master/app/views/layouts/application.html.erb#L10
* https://github.com/Bahanix/ocr-rails-5/tree/master/app/views/books

# Pour lancer l'application :

Exécuter dans un terminal :

```
git clone https://github.com/Bahanix/ocr-rails-5.git
cd ocr-rails-5/
bundle install
rake db:migrate
rails server
```

Puis se rendre sur : http://localhost:3000/books
