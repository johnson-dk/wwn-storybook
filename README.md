# Storybook static site

This is just for publishing the static site created by Storybook


[Read more here](https://storybook.js.org/docs/basics/exporting-storybook/) 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage
Only changes in master should be built and pushed to master.

If you would like to share changes that are not yet in master you can just create a branch,
this will be built and visible on {branch-name}--wwn-storybook.netlify.app 

*An Example*
```bash
git checkout -b my-awesome-change
git add .
git commit -m "my awesome change I want to share"
git push -u origin my-awesome-change
```

After a minute you should see you changes visible at https://my-awesome-change--wwn-storybook.netlify.app

## Contributing
After updating Storybook and getting your changes into master

```bash
# Run this command from the main project
npm run build-storybook
# change into the wwn-storybook directory
git add .
git commit -m "New story added for a component"
git push
``` 

Then check it all looks good at

## License
[MIT](https://choosealicense.com/licenses/mit/)

Run `npm run build-storybook` from the wwn project
Then 
