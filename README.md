![hapi from scratch](https://guides.nanobox.io/assets/quickstart-icons/hapi.png)

# hapi from scratch

Run an hapi app locally, install nothing besides nanobox. 

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-hapi.git

# cd into the hapi app
cd nanobox-hapi
```

## Run the app

```bash
# Run hapi as you would normally, with Nanobox
nanobox run npm start
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local hapi.dev
```

Visit your app at <a href="http://hapi.dev:3000" target="\_blank">hapi.dev:3000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# your packages are available,
npm list

# and your code is mounted
ls
```

## Now What?
For more details about running hapi apps with nanobox visit [guides.nanobox.io/nodejs/hapi/](https://guides.nanobox.io/nodejs/hapi/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
