FissionInvoice
==============

This project is sorta "personal" improvement over the very first version of FusionInvoice. Of the many web-based invoicing solutions I've tested, Fusion was the simpler and nicer (to me).

It's based on CodeIgniter framework, I worked with a lot in the past. As old and simple as it is, it's more than adequate for such a simple domain, plus it runs fast and could be deployed to pretty every single cheap hosting in the world.
So, even if Rails or Sinatra + AngularJS would have been way much cooler (and who knows in the future...), I decided to put some love in this product.

The base for this work is FusionInvoice 1.3, so the heavy work has been done by Jesse Terry (thanks Sir).

As the moment of writing the branching model I went with is *git-flow*, with twists:

* `master` is the release branch
* `develop` is where I integrate the development
* `feature/*` and `hotfix/*` are as for the git-flow
* `agavee` contains custom code I need to run my company

If you want to send me pull requests on the development version, use develop.
If you want to send changes to a specific version, fork from master, based on the release tag.