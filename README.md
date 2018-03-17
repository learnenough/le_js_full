# Sample app with gallery

This is the full starting application (with image gallery) for the final chapter of [*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial) by Michael Hartl, based on the sample application developed in [*Learn Enough CSS & Layout to Be Dangerous*](https://www.learnenough.com/css-and-layout-tutorial) by Lee Donahoe and Michael Hartl.

To get started, first for the repository using the **Fork** button on the upper-right of the screen.

The next step depends on whether or not you currently have a default GitHub Pages site at &lt;your username&gt;.github.io (as developed in [*Learn Enough CSS & Layout to Be Dangerous*](https://www.learnenough.com/css-and-layout-tutorial)).

If you don't have such a repository, you can clone the gallery app there directly:

```
$ git clone <clone URL> <your username>.github.io
```

Then create a new repository of that name at GitHub and push up.

If you already have such a repository, you should clone the gallery app to the default directory:

```
$ git clone <clone URL>
```

This will create a local repository called `le_js_full`, which you can use as a reference for copying over the required files. In particular, you'll need the gallery `index.html` and the large and small images:

```
$ cd le_js_full/
$ cp gallery/index.html /path/to/repo/<your username>.github.io/gallery/
$ cp -r images/* /path/to/repo/<your username>.github.io/images/
```

In either case, you can run the app using the `jekyll` static site builder:

```
$ jekyll serve
```

At that point, the app will be running on [localhost:4000](http://localhost:4000). To deploy your app, push up the app to GitHub Pages as [described](https://www.learnenough.com/css-and-layout-tutorial/css/introduction/sample_site_setup) in [*Learn Enough CSS & Layout to Be Dangerous*](https://www.learnenough.com/css-and-layout-tutorial).
