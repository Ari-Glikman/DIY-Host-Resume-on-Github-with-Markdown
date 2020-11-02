# How To: Format and Host Your Resume on GitHub Using Markdown

This README will explain from scratch how to host a resume (made with markdown) on GitHub pages. On the way you will learn to about Technical Writing through the ideas developed in Andrew Etter's *Modern Technical Writing*. 
________________


### Purpose

Why would you want to create a resume with markdown and host it on GitHub in the first place? 

For starters, markdown is one of the most popular lightweight markup languages, since it is easy to learn (especially easier than HTML) and still converts to HTML quickly. Learning to use it will be useful as it is used everywhere on the internet!             
Secondly, static websites, as Andrew Etter will tell you, are everywhere and anywhere. On top of that, they are easy, secure, fast, and portable. By hosting your resume on GitHub pages you will be utilizing one yourself.

Lastly, having your resume online is a no-brainer if you are in tech. As a bonus GitHub pages will also give you a nice URL, which will look impressive and allow yourself to look like the polished person you are.

### Pre-requisites
What are you going to need before you get started? You will need the following: 

1. Some Markdown Know-how
    * You can learn quickly [here.](#more-Resources) 
    
2. A Resume Formatted In Markdown
    * Feel free to use my [template.](https://github.com/Ari-Glikman/Ari-Glikman-Resume/edit/gh-pages/index.md)

3. A GitHub account
    * Don't have one? No problem. Make one [here](https://github.com/).
    
    
### Instructions

The steps will be simple easy to follow.

#### 1. Create a new repository on GitHub (and make sure it is public)

If you are in tech it is likely that potential employers are active on GitHub. It is then important that you make yourself visible to them. As Etter says **Define the Audience.** By wanting to get your resume on GitHub you have done just that.

All the material that you will need will exist within a single repository on GitHub. You can go ahead and create one by cliking the '+' at the top right corner of your GitHub page and select 'New repository'. 

![Newrepository](https://user-images.githubusercontent.com/73805987/97831667-5912ab80-1c96-11eb-9281-6dd94da0854d.jpg)

Next you will want to create a name and a description as well. Here you should again take into account the purpose of technical communication as worder perfectly by Etter "Write down exactly what an audience needs to know and *no more*". Scroll down and ensure that it is public (if it's not you will not be able to host it on GitHub pages under a unique URL). 

Your page should look something like this:

![image](https://user-images.githubusercontent.com/73805987/97832778-48176980-1c99-11eb-86c6-f85b40c05b76.png)


It will be simpler for you if you **do not** initialize your repository with anything for now. Unless you are experienced and know that doing otherwise will be best for you then go ahead.

Go ahead and click 'Create repository'.


#### 2. Enable GitHub Pages 

Etter states simply and clearly that building and hosting a website is superior to distributing PDFs in technical writing. This applies to your resume too.

To enable GitHub Pages you will have to first change your repsotiory's settings. 

![Settings](https://user-images.githubusercontent.com/73805987/97833455-0091dd00-1c9b-11eb-93a9-265333da3ca8.png)


Once you have clicked on settings scroll down to the section titled 'GitHub Pages'.

It should look like this: 

![GHPages](https://user-images.githubusercontent.com/73805987/97833160-574ae700-1c9a-11eb-92dd-ddb9299e4000.jpg)

Click 'Choose a theme'. Here you will have several options. Explore which you like best for your resume and click 'Select theme'. (This is not final, you can change your theme at any time)

#### 3. Choose a template for your resume

Style can be the difference between someone reading your work and skimming over it. As *Modern Techincal Writing* suggests, style your resume appropriately, but do not obsess.

Remember the static websites that are so handy? You are going to go ahead and use it now. Though there are many to choose from, the one you are going to use today is Jekyll. Don't worry: you do not have to know what Jekyll is or how to use it, but just know that you will use it as your static site generator. 

![Themes](https://user-images.githubusercontent.com/73805987/97833904-1ce24980-1c9c-11eb-8d5b-e465e3030b74.png)

Once you do this you will be taken to edit a new file in your repository. This file is called *index.md* and it will be where you put your resume. 

![index](https://user-images.githubusercontent.com/73805987/97835006-c9252f80-1c9e-11eb-9903-27b1e90366c9.png)


#### 4. Upload your resume in Markdown

You have to market yourself as a product. To paraphrase Etter, why whould anyone want you? How would you fit in a broader ecosystem? Your resume should be to you what product documentation is to a product.

There is a few ways to go about uploading. If you already have your file in a .md file you can click 'Upload files' and upload your file.

![Upload](https://user-images.githubusercontent.com/73805987/97834518-a7777880-1c9d-11eb-8047-8ed9f738d451.png)

If you do not have your resume in markdown format go ahead and right it here. The first time I made my resume in markdown I used a very handy [website](https://markdownlivepreview.com/) that gave a live preview of what was being written. Once I was satisfied I copied everything over to the *index.md* file.

Some tips for writing your resume that apply to Technical Writing as well:
* Start with a simple statement of purpose
* Tell what is necessary and nothing else
* List items in order of decreasing importance (people exponentially get lazier the more they read)

Scroll to the bottom and select 'Commit changes'.

![resume](https://user-images.githubusercontent.com/73805987/97835723-6f256980-1ca0-11eb-958b-eec9d316312b.png)

#### 5. Show. It. Off.

Congratulations! You now host your resume on GitHub Pages. Check it out by visiting your URL.

![Alt text](https://media.giphy.com/media/jAzP6ubqXn5miQrTAm/giphy.gif)

One last lesson Etter teaches is to publish documentation frequently. Since your resume is now public, you do not know when it will be glared at, nor by whom. Hence: update, update, update. 

### More Resources

Do you want to learn more about markdown? Do so [here.](https://www.markdowntutorial.com/)

Get Andrew Etter's [*Modern Technical Writing.*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

Are you still curious about creating static websites using Jekyll? Look no [further.](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages)

### Authors and Acknowledgements

I would like to thank Ryan Shaski for his resume template and my group members: Michael Kolisnyk, Darshan Pandhi, and Farjad Tariq for giving me direction and creative ideas on creating my resume and README files.

### FAQ

1.  Why should I use Markdown instead of a word processor?

    * Great Question! In short, Markdown is more flexible. It does not depenend on an operating system, platform, and last but not least it is everywhere including on the front page of the [internet](https://www.reddit.com/).



2.  What if I want my resume to display on my profile?

    * That's possible too. Rename your index.md file to README.md. It should now show up on your profile (as your profile's README).  

