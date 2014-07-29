# Larabook


Just following the tutorial of Jeffrey Way on Laracasts. Here is a quick reminder of the topics covered in the lessons.

## Disclaimer

This is just a project to help you if you are following along [Jeffrey Way](https://github.com/JeffreyWay)'s Larabook lessons on [Laracasts](http://laracasts.com). If you want to learn more about the concepts here and about the Laravel framework usage, please visit and subscribe to Laracasts (it is worth it!).

## Lessons summary

### 1. [The Virtual Machine](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/1)

To begin our new project, let's setup a virtual machine, using Vagrant and Laravel Homestead.

**Please note: I did not actually followed this lesson, so the projet in this repository may be a little bit different**

### 2. [Dependencies](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/2)

There are a number of dependencies that we'll need to pull in for this project. While even a few years ago, this might have been a pain, luckily that's no longer the case, thanks to Composer.

### 3. [Database Configuration and Sequel Pro](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/3)

In this lesson, let's get connected to our database, and then figure out how to access it from a GUI, like Sequel Pro.

**Please note: All `.env.*.php` files are of course not committed, please check the lesson to know how to create them.  **

### 4. [The Master Page](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/4)

Although we won't focus too much on design, naturally, we need something nice and simple to look at. So, let's begin that process by leveraging Twitter Bootstrap, and setting up our first master/layout page.

### 5. [Designing the Home Page](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/5)

This includes some basic design boilerplate work. Let's focus on the navbar and homepage in this episode.

### 6. [Gulp, Sass and Autoprefixing](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/6)

Let's put a system into place, that will automatically watch our Sass files for changes, compile them, and then autoprefix any relevant CSS3. We'll use the excellent Gulp tool to allow for this.

### 7. [Registration with BDD](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/7)

Naturally, before a user can begin posting status updates, they first need to register for Larabook. Let's use Codeception to help drive and test this process.

### 8. [Users](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/8)

In the previous lesson, we stopped just short of creating a migration for our users. Let's tackle that now, and return the tests to green.

### 9. [Registration Validation](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/9)

Of course, form validation is essential for any web app. Larabook is no different; so let's work on that in this episode.

### 10. [Thinking in Terms of Commands](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/10)

For larger applications that need to be maintained for years, it makes sense to take a step back, and think about architecture. Let's use commands to describe the various instructions that our app offers, as well as a command bus to manage the act of translating these commands into handler classes.

### 11. [Domain Events](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/11)

Because we've taken some time to structure our app in this manner, we now have a really simple way to queue and listen for domain events. Let me show you.

### 12. [Super Easy Flash Messaging](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/12)

How many times have you created the necessary views to display flash messages? Lots? Well, in this episode, I'll show you how we can tackle this very quickly.

### 13. [Feedback and Filters](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/13)

Right now, we can register a user; however, we still need to provide more feedback to signal that they are, in fact, logged in. Let's focus on that in this episode, along with a few other tidbits.

### 14. [Signing In](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/14)

Now that a user can successfully register, we next need to give them a way to login and logout!

### 15. [Returning the Tests to Green](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/15)

If you're working along, you might have encountered a confusing Codeception bug. Don't worry: as they say, it's Codeception, not you. Let's take a look.

### 16. [Publishing Statuses](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/16)

It's time to allow our authenticated users to publish statuses to their profile. We have a number of things to do in this episode, so grab a cup of coffee, and let's do this.

### 17. [Integration Testing Repositories](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/17)

So far, we've exclusively created functional tests. However, often, it can be beneficial to test at a lower level. In this episode, we'll setup Codeception to execute our integration tests, using a repository as an example. Hopefully, you'll see just how easy it can be.

### 18. [Gravatars and View Presenters](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/18)

At least for now, rather than making Larabook users upload profile images, we'll simply leverage the popular Gravatar service. Along the way, I'll show you three different ways to "store" this logic for fetching the appropriate Gravatar.

### 19. [Designing Statuses](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/19)

Right now, the status page looks terrible. I know we're interested in the code, but let's take at least ten minutes to make it look prettier.

### 20. [Dummy Users and Statuses](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/20)

So far, we've been manually creating records. Naturally, though, it makes sense to mass-create users and statuses, for the purposes of testing in the browser. Let me show you a streamlined way to accomplish this.

### 21. [Browsing Users With Pagination](https://laracasts.com/series/build-a-laravel-app-from-scratch/episodes/21)

We need to offer some way for users to browse through all registered members of Larabook. That way, they can have the option of "following" any developers who post interesting statuses. Let's handle that in this lesson, while also implementing pagination.