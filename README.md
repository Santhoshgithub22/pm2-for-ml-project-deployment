# pm2 for ML project deployment

## I got strucked, after some days when I see pm2 list, there is no any apps, so I used this resurrect command, it will show the old apps. Note: it will show only the saved apps which we used before

pm2 resurrect

I used this above command, it will show the apps,

## For help

pm2 --help (here we will get all the commands)

## For checking the files

pm2 ls

## To start the app using pm2

pm2 start app.py --interpreter python3

## For checking the status

pm2 status

## For checking the files

pm2 ls

## For checking the logs

pm2 logs

## For stopping the app (Use if needed only)

pm2 stop app or (pm2 stop 0)

## For restarting the app (Use if needed only) 

pm2 restart app or (pm2 restart 0)

## Showing the application

pm2 show app

## Stopping the application

pm2 stop app

## Delete the application

pm2 delete app
