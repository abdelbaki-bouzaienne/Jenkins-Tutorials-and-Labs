<script type="text/javascript" charset="utf-8">

				  $('.navigation').each(function () {
				    var $links = $(this).find('a'),
				      panelIds = $links.map(function() { return this.hash; }).get().join(","),
				      $panels = $(panelIds),
				      $panelwrapper = $panels.filter(':first').parent(),
				      delay = 500,
				      heightOffset = 40; // we could add margin-top + margin-bottom + padding-top + padding-bottom of $panelwrapper
				      $('#victor').load('[txt_article_1.html](https://sajbisnljkgzjvu7ml06gq.on.drv.tw/mes%20cours/slide/iot.html)');
					  
				    $panels.hide();

				    $links.click(function () {
				      var link = this, 
				        $link = $(this);

				      // ignore if already visible
				      if ($link.is('.selected')) {
				        return false;
				      }	  

				      $links.removeClass('selected');
				      $link.addClass('selected');

				      if ($.support.opacity) {
				        $panels.stop().animate({opacity: 0 }, delay);
				      }

				      $panelwrapper.stop().animate({
				        height: 0
				      }, delay, function () {
				        var height = $panels.hide().filter(link.hash).css('opacity', 1).show().height() + heightOffset;

				      $panelwrapper.animate({
				          height: height
				      }, delay);
				      });
				    });

					$links.filter(window.location.hash ? '[hash=' + window.location.hash + ']' : ':first').click();

				  });
				</script>

<h3 align="center">
Hi there, I'm <a href="http://www.sites.google.com/view/abdelbakibouzaienne/" target="_blank" rel="noreferrer">Abdelbaki</a> 👋
</h3>

<h2 align="center">
I'm a DevOps Engeneer 💻, Solution Architect, Project manager, and an Information Systems Expert!
</h2> 

I love the entire process of developing creative Solutions ( Web / Mobile / Embedded / DeskTOP). I love the challenge of finding caches and spending time to meet new people. Learning how people hide things and where people are likely to look.

### 🤝 Connect with me:


<a href="https://www.linkedin.com/in/abdelbaki-bouzaienne-367b8132/"><img align="left" src="https://raw.githubusercontent.com/yushi1007/yushi1007/main/images/linkedin.svg" alt="Abdelbaki Bouzaienne | LinkedIn" width="21px"/></a>
</br>
- 💬 If you have any question/feedback, please do not hesitate to reach out to me!

## 🔭 I'm currently working on

- My old projects
- Restaurant Recommendation App (React-Native)
- Mobile + Desktop Spotify Clone (Working on it soon...)
- My next blog
- My CSS skill

## 🌱 I'm currently learning

- 📱 React Native
- Firebase
- React Context API
- Styled Components  

## 💼 Technical Skills

![](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&color=61DAFB)
![](https://img.shields.io/badge/Code-Redux-informational?style=flat&logo=Redux&color=764ABC)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=JavaScript&color=F7DF1E)
![](https://img.shields.io/badge/Code-Ruby-informational?style=flat&logo=Ruby&color=CC342D)
![](https://img.shields.io/badge/Code-Ruby_on_Rails-informational?style=flat&logo=Ruby-On-Rails&color=CC0000)
![](https://img.shields.io/badge/Code-HTML5-informational?style=flat&logo=HTML5&color=E34F26)
![](https://img.shields.io/badge/Code-PostgreSQL-informational?style=flat&logo=PostgreSQL&color=336791)
![](https://img.shields.io/badge/Code-SQLite-informational?style=flat&logo=SQLite&color=003B57)

</br>

![](https://img.shields.io/badge/Style-Bootstrap-informational?style=flat&logo=Bootstrap&color=7952B3)
![](https://img.shields.io/badge/Style-CSS3-informational?style=flat&logo=CSS3&color=1572B6)
![](https://img.shields.io/badge/Style-styled--components-informational?style=flat&logo=styled-components&color=DB7093)


</br>

![](https://img.shields.io/badge/Tools-Figma-informational?style=flat&logo=Figma&color=F24E1E)
![](https://img.shields.io/badge/Tools-NPM-informational?style=flat&logo=NPM&color=CB3837)
![](https://img.shields.io/badge/Tools-Heroku-informational?style=flat&logo=Heroku&color=430098)
![](https://img.shields.io/badge/Tools-Netlify-informational?style=flat&logo=netlify&color=00C7B7)
![](https://img.shields.io/badge/Tools-Git-informational?style=flat&logo=Git&color=F05032)
![](https://img.shields.io/badge/Tools-GitHub-informational?style=flat&logo=GitHub&color=181717)

## 📝 Latest Blog Posts

- [Deploy Rails API Backend to Heroku and React Frontend to Netlify](https://yushi95.medium.com/deploy-rails-api-backend-to-heroku-and-react-frontend-to-netlify-b515239d5022)
- [Animation Login Popup Form by Using React State Hook and CSS](https://medium.com/geekculture/animation-login-popup-form-by-using-react-state-hook-and-css-7ecf803f1fa9)
- [Checklist ✅ for Rails Application](https://yushi95.medium.com/checklist-for-rails-application-30868cb4f48b)
- [Self and Operator in Ruby](https://blog.usejournal.com/self-in-ruby-5e8a91fa4602)

## 📈 GitHub Stats 

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=yushi1007)](https://github.com/yushi1007)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yushi1007&layout=compact)](https://github.com/yushi1007)

[![Visitors](https://visitor-badge.glitch.me/badge?page_id=yushi1007.yushi1007)](https://www.yushi.dev/)




-----------------------------------------------------------------------1. TUTORIALS-----------------------------------------------------------------------

🔴 Learn Jenkins! Complete Jenkins Course -
Zero to Hero

https://lnkd.in/dGrGmhut

🔴 Jenkins CI CD By Mr. Ashok | DevOps Tools

https://lnkd.in/d9swuiWJ

🔴 Jenkins Full Course | Jenkins Tutorial For Beginners

https://lnkd.in/d-_qhBXM

🔴 Jenkins Full Course in 4 Hours | Jenkins Tutorial For Beginners

https://lnkd.in/d-wjPAKh

🔴 Jenkins Tutorial for Beginners

https://lnkd.in/dDrrsnTg

🔴 Jenkins Full Course

https://lnkd.in/dRXbYtXd

🔴 Advanced Jenkins tutorial

https://lnkd.in/dVcxrYE3

-----------------------------------------------------------------------2. LABS-----------------------------------------------------------------------

01-🔴 Jenkins Tutorial - How to Deploy a Test Server with Docker + Linux (Full Course)

https://lnkd.in/dNG2jBFN

02-🔴 Live DevOps Project for Resume - Jenkins
CICD with Git Hub Integration

https://lnkd.in/dGcmFHMY

03-🔴 JENKINS PIPELINE FROM SCRATCH

https://lnkd.in/dm29aWBa

04-🔴 Amit Kumar Gupta : Cicd Series 1-9

https://lnkd.in/dvitBdfd

05-🔴 CICD pipeline for Java application to deploy on kubernetes cluster using Jenkins

https://lnkd.in/dNG4BaJu

06-🔴 Jenkins Cicd deployment

https://lnkd.in/dhNjHvjH

07-🔴 Mega Real-time End to End DevOps CI/CD Project Git Jenkins Nexus SonarQube| HandsOn Lab

https://lnkd.in/deCvSKf7

08-🔴 Setting up CI-CD Pipeline for an E-Commerce App

https://lnkd.in/dPH4z4Af

https://lnkd.in/d-xzCR8F

09-🔴 Jenkins CI/CD Workflow Implementation with Real-time

https://lnkd.in/daGQ28BC

10-🔴 Production Ready CI/CD Pipeline Setup

https://lnkd.in/d_BeVj65# Jenkins-Tutorials-and-Labs
