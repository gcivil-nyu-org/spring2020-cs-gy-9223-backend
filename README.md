`develop`

[![Build Status](https://travis-ci.com/gcivil-nyu-org/spring2020-cs-gy-9223-backend.svg?branch=develop)](https://travis-ci.com/gcivil-nyu-org/spring2020-cs-gy-9223-backend)
[![Coverage Status](https://coveralls.io/repos/github/gcivil-nyu-org/spring2020-cs-gy-9223-backend/badge.svg?branch=develop)](https://coveralls.io/github/gcivil-nyu-org/spring2020-cs-gy-9223-backend?branch=develop)

`master`

[![Build Status](https://travis-ci.com/gcivil-nyu-org/spring2020-cs-gy-9223-backend.svg?branch=master)](https://travis-ci.com/gcivil-nyu-org/spring2020-cs-gy-9223-backend)
[![Coverage Status](https://coveralls.io/repos/github/gcivil-nyu-org/spring2020-cs-gy-9223-backend/badge.svg?branch=master)](https://coveralls.io/github/gcivil-nyu-org/spring2020-cs-gy-9223-backend?branch=master)

# Team Project repo

Heroku Production (master) URI: [https://mecury-backend-prod.herokuapp.com/](https://mecury-backend-prod.herokuapp.com/)

Heroku Staging (develop) URI: [https://mecury-backend.herokuapp.com/](https://mecury-backend.herokuapp.com/)

Heroku Dashboard: [https://dashboard.heroku.com/pipelines/0ecdbb08-017b-4ea2-8969-d6b7dadb9888](https://dashboard.heroku.com/pipelines/0ecdbb08-017b-4ea2-8969-d6b7dadb9888)


# First time repo setup
1. From the root of the repo, run `scripts/setup.sh`. Activate your virtualenv first.
2. To run the server, run `python manage.py runserver`.

You should now be able to view the site at http://127.0.0.1:8000/

# HOWTO Contribute to this repo

N.B.: `<something>` means you need to change the `something` text within the angle brackets (and do not include the include brackets in your command).
1. Make a feature branch
`git checkout -b <new_branch_name>`
2. Make your changes
3. Check you are using consistent style by running `scripts/check.sh` and make any recommended changes (such as running black to re-format).
4. Run your tests with `python manage.py test` and fix errors.
4. Use `git add <filename> ...` to add files you changed or more conveniently, `git add -A`.
5. Commit your changes with `git commit -m "<message_of_what_this_commit_does>"`.
6. Push your branch to the origin fork with `git push origin <new_branch_name>` of the branch you made locally.
7. Visit [our repo](https://github.com/gcivil-nyu-org/fall2019-cs-gy-6063-team-moonsurvivors/pulls) to create a Pull Request or use the link that the `git` command printed for you.
8. Add someone on the team as a review or share your URL to the Slack channel.

# Fix issues
Running into issues with modules not find? Did `requirements.txt` update from your last `git pull` command? Run `pip install -r requirements.txt` to install missing modules.

Are you missing staticfiles when trying to run or test locally? Run `python manage.py collectstatic` to regenerate them.

# HOWTO Run the app locally
Run `python manage.py runserver` from the root of this Git repo

# HOWTO Run tests locally
Run `python manage.py test`
