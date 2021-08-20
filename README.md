<div  align="center">
	<a  href="https://summerofcode.withgoogle.com/projects/#6282404605460480"><img  src="https://user-images.githubusercontent.com/50985033/130266342-89a9b5ed-31b2-4202-9b69-09b7157fe117.png"  width="650"  alt="google-summer-of-code"></a>
	<br>
	<b>
		<h1>
		Sugarizer Security and Availability
		</h1>
	</b>
</div>

In May of 2021, I was selected for Google Summer of Code'21 to work with [Sugar Labs](https://github.com/sugarlabs/). My project goals were to improve security and availabilty of Sugarizer and other projects affiliated with it namely: 
[Sugarizer-School-Portal-Server](https://github.com/NikhilM98/sugarizer-school-portal-server), 
[Sugarizer-Chart](https://github.com/NikhilM98/sugarizer-chart), 
[Sugarizer-School-Portal-Chart](https://github.com/NikhilM98/sugarizer-school-portal-chart) and 
[Sugarizer-Server](https://github.com/llaske/sugarizer-server)

<div  align="center">

![enter image description here](https://media.giphy.com/media/l0K4hO8mVvq8Oygjm/giphy.gif)

</div>

## 📙 Abstract

[Sugarizer](https://sugarizer.org/) is a free/libre learning platform. The Sugarizer UI use ergonomic principles from The [Sugar platform](https://sugarlabs.org/), developed for the One Laptop per Child project and used by more than 2 million children around the world.

Sugarizer runs on every device: laptops, desktops, tiny computers, tablets or smartphones.

Sugarizer includes a large set of pedagogic activities thought for children, see [here](https://sugarizer.org/activities.html) for a full list.

Sugarizer is available as:

* Application: an installable app for every operating system
* Web Application: a web application that runs in modern web browsers

**Thanks to former GSoC Projects, Sugarizer can easily be deployed on Kubernetes clusters to meet some users deployment expectations.**
**The objective of this project is to keep Sugarizer growing by enhancing two core concepts for our deployments: Security and Availability.**

## 📝 Deliverables

The deliverables of the project are as follows:

- [x] Learn about 2FA and TOTP code generation
- [x] Fix current issues/features request on [Sugarizer-School-Portal](https://github.com/NikhilM98/sugarizer-school-portal-server/issues)
- [x] Update package/chart versions for Sugarizer School Portal.
- [x] Migrate from deprecated [helm/mongodb-replicaset](https://github.com/helm/charts/tree/master/stable/mongodb-replicaset) chart to [bitnami/mongodb](https://github.com/bitnami/charts/tree/master/bitnami/mongodb) chart.
  - While maintaining support on different Kubernetes providers.
- [x] Add TOTP registration feature to Sugarizer School Portal to enhance user's security.
  - Enable and Disable feature
  - TOTP Verification upon enabling Two Factor Authentication.
- [x] Add TOTP registration feature to the Sugarizer Dashboard to enhance user's security.
- [x] Update the prevailing tests and write tests for new features added.


All of the aforementioned deliverables were attained during GSoC coding period. 🎉