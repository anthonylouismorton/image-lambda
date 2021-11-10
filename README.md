# image-lambda

## how to use your lambda
Lambda works by creating a images.json when one doesn't exist. When one exists the lambda will add an image to the images.json that was added to the bucket the lambda targets. The lambda is triggered on a put. The images.json is then uploaded back to the bucket.

## issues you encountered during deployment of this lambda
Had issues with recursion. Had issues with getting the proper data in the package.json. Issues with permissions.

## link to your images.json file
https://anthonymortonlab17.s3.us-west-1.amazonaws.com/images.json