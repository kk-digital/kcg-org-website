## KK Digital Website

### Setup

#### Install Hugo

##### Linux

Download the Hugo package for your distribution from the [Hugo release page](https://github.com/gohugoio/hugo/releases) and install the latest version. 

##### MacOS

Make sure you have [Homebrew](https://brew.sh/) installed. Afterwards run:

```
brew install hugo
```

##### Windows

Make sure you have [Chocolatey](https://chocolatey.org/) installed. Afterwards run:

```
choco install hugo -confirm
```

#### Run website locally

Ensure you have Git installed. Afterwards run:

```
git clone https://github.com/kk-digital/kk-digital-website.git
```

Change directory into the repo

```
cd kk-digital-website
```

Run the hugo server with:

```
hugo server
```

The website will be exposed on `localhost`. The port will be specified in the console output of the above command.