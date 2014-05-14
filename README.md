martini_gorelic
=============

martini_gorelic is NewRelic middleware for martini framework.

# Installation
 - Run "go get github.com/yvasiyarov/martini_gorelic"
 - Add following lines to your main() function:
  martini_gorelic.InitNewrelicAgent("7bceac019c7dcafae1ef95be3e3a3ff8866de266", "test martini app", true)
  m.Use(martini_gorelic.Handler) //m - is martini application instance

Please, dont forget to change NewRelic license to your license
