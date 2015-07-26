# APIBlueprint
The templating for the new doumentation is using [APIBlueprint](https://apiblueprint.org/) markdown.

If you find any mistakes, or see room for improvement, pull requests are welcomed!

**For functionality syntax**, you can take a look at [this guide](https://apiary.io/blueprint) for the basics, and [this guide](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md) for a very detailed documentation on the markdown language. 

**For style/appearance**, please take a look [here](http://apiary-embed.herokuapp.com/api-reference.html).
For example, as it stands, the style has been changed to the following (not found in the markdown):
```
<script type="text/javascript">
var embed = new Apiary.Embed({
		subdomain: 'blockchaininfo',
		theme: {
			fontFamily: 'Helvetica',

			tableOfContents: {
				section: {
					title: {
						color: '#049BD4'
					}
				}
			},

			humanColumn: {
				content: {
					section: {
						title: {
							color: '#049BD4'
						}
					}
				}
			},

			machineColumn: {
				content: {
					request: {
						controls: {
							tryButton: {
								color: '#049BD4'
							}
						}
					}
				}
			}
		},
		hosts: ['production']
});
</script>
```
This will be kept updated with any changes.
