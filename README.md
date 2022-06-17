# Scaffold for SLS (AWS) REACT WEBSITE

basic website scaffold with bootstrap css loaded.

## To use

You must have aws cli and serverless installed to use.

Clone the repo.

**_ There is an npm warning from bootstrap. Current fix is to go to and update the code: _**

```
(2482:3) autoprefixer: Replace color-adjust to print-color-adjust. The color-adjust shorthand is currently deprecated.
```

**_ in `node_modules/bootstrap/dist/css/bootstrap.css` _**

then `npm install`.

Change the bucket names in `serverless.yml`, for simple CNAME redirecting, the url must match the bucket name. So for example "www.mysite.com".

`sls deploy`.
