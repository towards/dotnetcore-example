# ASP.NET Core example web app for Gleis PaaS

This is a simple ASP.NET Core example web app made for the [Gleis Platform as a Service](https://gleis.cloud).

## Prerequisites

In order to run this example web app locally you will need the [.NET Core Runtime or SDK](https://dotnet.microsoft.com/) to be installed on your computer. To deploy it on Gleis you will need the [Gleis CLI Ruby gem](https://rubygems.org/gems/gleis) and an [account on the Gleis PaaS](https://gleis.cloud).

## Try the example web app locally

Download your own copy of this web app:
```sh
$ git clone git@github.com:towards/dotnetcore-example.git
```

Run the web app:
```sh
$ cd dotnetcore-example
$ dotnet run
```
The example web app should now be reachable locally at [http://localhost:5000](http://localhost:5000)

## Deploy the web app to the Gleis PaaS

Create new app on Gleis:
```sh
$ gleis app create
```

Upload app to Gleis:
```sh
$ git push gleis master
```

The example app will be online in a few seconds and reachable through the HTTPS URL mentioned when you created the Gleis app with the above command.