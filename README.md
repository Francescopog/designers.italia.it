# Sorgenti del sito di Designers Italia

[![CircleCI](https://circleci.com/gh/italia/designers.italia.it.svg?style=svg)](https://circleci.com/gh/italia/designers.italia.it)

Questo repository contiene il codice sorgente di [Designers Italia](https://designers.italia.it), **il punto di riferimento per la progettazione dei servizi pubblici digitali**.

Il repository contiene anche alcuni asset (es. file sketch) o i riferimenti agli asset (es. link a un documento docs italia, oppure a un altro repo specifico) dei kit per il design della Pubblica Amministrazione italiana.

Ogni commento o proposta relativa all'evoluzione dei kit può essere fatta utilizzando le [issues](https://github.com/italia/designers.italia.it/issues) di GitHub.

Il sito è sviluppato con [Jekyll](https://jekyllrb.com/) e fa uso dell'ecosistema [Node.js](https://nodejs.org/it/) con [Yarn](https://yarnpkg.com/lang/en/).

Per configurare un ambiente di sviluppo è sufficiente eseguire i seguenti comandi:

    $ yarn install
    $ bundle install
    $ bundle exec jekyll serve

In caso di problemi con l'installazione di rmagick 4.1.2 su recenti OSX, [quest pagina](https://stackoverflow.com/questions/41647979/imagemagick-7-with-rmagick-2-16-on-macos-sierra-cant-find-magickwand-h) potrebbe essere d'aiuto.

Se vuoi contribuire e proporre una modifica, è sufficiente aprire una [pull request](https://github.com/italia/designers.italia.it/pulls) su GitHub.

Il sito necessita di essere ricompilato ad ogni pubblicazione su Medium.
