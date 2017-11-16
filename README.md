This is a very simple webpage for personal usage using [hugo](https://gohugo.io) and App Engine.

Hosted on App Engine, it provides a simple way to display a list of links
and redirect automatically based on its path.

All this information is stored in the datastore, and for now there's no
managing tool other than the App Engine datastore viewer.

Given a link with name "Twitter", path "+", and a url "http://twitter.com/francesc"
the link will appear on the list as a link with text "Twitter" pointing to the given url,
and the path "/+" will redirect to the twitter url automatically.

It serves http://campoy.cat.
