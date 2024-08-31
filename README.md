# Drawio Site

This is a template repository for web sites generated from Drawio diagrams with [GitHub Actions](https://docs.github.com/en/actions) and [Nasdanika CLI Drawio Command](https://docs.nasdanika.org/nsd-cli/nsd/drawio/index.html).


## Demos

Below is a list of sites created from this template:

...

## Steps

* On the [repository page](https://github.com/Nasdanika-Templates/drawio-site) click "Use this template" button in the top right.
* You may rename ``diagram.drawio`` to something more meaningful, e.g.``my-system.drawio``. Or you may use a pre-existing drawio diagram and delete ``diagram.drawio``. If you do rename/replace the deiagram, open ``.github/workflows/site.yml`` and update line 40 with a new diagram file name.
* Once you create a new repository, go to the Settings > Pages and select "GitHub Actions" as source.
* Click on the Acitons tab and check the status of ``Generate HTML Site from a Drawio diagram with Nasdanika CLI`` action. Once it is successful, open the pages site.
* Customize the diagram, root action, and page template to your needs as explained below.

## Deployment process

* Nasdanika CLI is downloaded and extracted
* Drawio ... command is executed to generate a site
* The generated site is deployed to GitHub Pages. 

## Page template

## Root action

## Failing on errors

## Spec

...

	/**
	 * Default base URI for the Drawio application to resolve library relative URL's.
	 */
	public static final URI DEFAULT_APP_BASE = URI.createURI("https://app.diagrams.net/");
	
	public static final String DOC_FORMAT_PROPERTY = "doc-format";
	public static final String DOC_REF_PROPERTY = "doc-ref";
	public static final String DOCUMENTATION_PROPERTY = "documentation";
	public static final String TITLE_PROPERTY = "title";
	public static final String ICON_PROPERTY = "icon";

## Page and element links

## Multiple diagram pages


## Markdown 

TODO - copy demo or reference

## Adding support for documentation format

...

Custom CLI - see demo cli, modify workflow

## Upgrading NSD CLI version



## Next steps

### Executable diagrams

#### Dynamic proxy

#### HTTP Routes

### Semantic mapping
