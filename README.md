# # 2way is a private message app like 'saraha'
It is an easy to use app, for fun purpose only.

## # How to run the app
1. First of all you need to run your **SQL Database Server**
2. Then you need to **migrate** the database it will create DB automatically `npm run migrate`
3. For development `npm run dev`
4. For production `npm run start`

## # How to create Database Table ?
1. Run this `npm run migrate:create <table-name>`
2. OR Run this for many `npm run migrate:create <table-name1> <table-name2> ...`
3. Then migrate this table `npm run migrate`

## # How to drop Database Table ?
1. Run this `npm run migrate:drop <table-name>`
2. OR Run this for many `npm run migrate:drop <table-name1> <table-name2> ...`