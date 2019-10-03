<h2>Introduction</h2>
<p>AngularJS was born in 2009 and was founded by Misko Hevery and later acquired by Google. It is an excellent front-end JS framework that has been used in Google's many products. AngularJS has many features, the most central of which are: MVC, modularization, automated two-way data binding, semantic labeling, dependent injection, and so on.</p>
<h2>Context View</h2>
<p>We will discuss all external entities that Angular interacts with and the context in which they interact with each other in this section. Through this analysis, we want to get an overview of the ecosystem in which Angular resides through which we can identify dependencies and users of interest.</p>
<p>&nbsp;</p>
<p><strong>System scope</strong></p>
<p>According to the introduction of <a href="https://angular.io/">Angular at its website</a>, Angular is defined as &lsquo;<strong>Angular is a development platform for building mobile and desktop web applications using TypeScript/JavaScript and other languages.</strong>&rsquo; The scope of the software is clearly defined here. It is constrained to focus on one task, which is develop web applications, and on a specific platform.</p>
<p>The website also states some advantages and features of Angular.</p>
<p>&nbsp;</p>
<p><strong>DEVELOP ACROSS ALL PLATFORMS</strong></p>
<p>Learn one way to build applications with Angular and reuse your code and abilities to build apps for any deployment target. For web, mobile web, native mobile and native desktop.</p>
<p>&nbsp;</p>
<p><strong>SPEED&amp;PERFORMANCE</strong></p>
<p>Achieve the maximum speed possible on the Web Platform today, and take it further, via Web Workers and server-side rendering.</p>
<p>Angular puts you in control over scalability. Meet huge data requirements by building data models on RxJS, Immutable.js or another push-model.</p>
<p>&nbsp;</p>
<p><strong>INCREDIBLE TOOLING</strong></p>
<p>Build features quickly with simple, declarative templates. Extend the template language with your own components and use a wide array of existing components. Get immediate Angular-specific help and feedback with nearly every IDE and editor. All this comes together so you can focus on building amazing apps rather than trying to make the code work.</p>
<p>&nbsp;</p>
<p><strong>LOVED BY MILLIONS</strong></p>
<p>From prototype through global deployment, Angular delivers the productivity and scalable infrastructure that supports Google's largest applications.</p>
<p>&nbsp;</p>
<p><strong>External Entities</strong></p>
<p>The connections between Angular and its environment is summarized in the figure.</p>
<p>&nbsp;<img src="https://github.com/supercheerman/angular-1/tree/master/mypicture/1.png" alt="" /></p>
<p>The external entities can be split into three groups.</p>
<p>&nbsp;</p>
<ol>
<li>Competitors</li>
</ol>
<p>Angular is of course not the only platform that provides front-end functionalities. When Angular was initially created, products with the same function already exist on the market, but they have their own advantages and disadvantages. The following is a list of competitors that provide in some way the same functionalities that Angular provides.</p>
<p>&nbsp;</p>
<ul>
<li><a href="https://github.com/facebook/react">React</a></li>
<li><a href="https://github.com/vuejs/vue">Vue</a></li>
<li><a href="https://github.com/dojo/core">Dojo2</a></li>
<li><a href="https://github.com/emberjs/ember.js">Ember</a></li>
<li><a href="https://github.com/aurelia/framework">Aurelia</a></li>
</ul>
<p>&nbsp;</p>
<ol>
<li>Software Platform &amp; Dependencies</li>
</ol>
<p>Programming languages: Angular is almost entirely written in TypeScript and JavaScript and some other languages.</p>
<p>Platforms: Angular is well tested for compatibility on all three major operating systems (Linux, Windows, OSX), and it&rsquo;s also available on mobile.</p>
<p>Dependencies:</p>
<p>The packages listed in the&nbsp;<a href="https://angular.io/api/core/ResolvedReflectiveFactory#dependencies">dependencies</a>&nbsp;section of&nbsp;package.json&nbsp;are essential to&nbsp;<em>running </em>&nbsp;applications.</p>
<p>The&nbsp;<a href="https://angular.io/api/core/ResolvedReflectiveFactory#dependencies">dependencies</a>&nbsp;section of&nbsp;package.json&nbsp;contains:</p>
<p>Angular packages: Angular core and optional modules; their package names begin @angular/.</p>
<p>&nbsp;</p>
<p>Support packages: 3rd party libraries that must be present for Angular apps to run.</p>
<p>&nbsp;</p>
<p>Polyfill packages: Polyfills plug gaps in a browser's JavaScript implementation.</p>
<p>&nbsp;</p>
<p>More information is listed on their <a href="https://angular.io/guide/npm-packages">own website</a> to introduce their npm-packages.</p>
<p>&nbsp;</p>
<ol>
<li>Development &amp; Community</li>
</ol>
<p>A platform that plays an important role during development is GitHub, which is used for code versioning, issue tracking and project management. All code gets tested and integrated via continuous tools.</p>
<p>The main communication channel used in the development of Angular is through their GitHub repository and their mailing list. More open discussion is done via Stack Overflow and the Angular Gitter channel. The Angular developers also provide support to users through their own website.</p>
<ol>
<li>Users</li>
</ol>
<p>The users of Angular can be divided into two subcategories. The individual community and enterprise.</p>
<p>Individual community</p>
<p>The individual community are the types of users that uses Angular as hobby for research. They do not intend to make money by using Angular. Such users are developers and universities.</p>
<p>Enterprise</p>
<p>Enterprise are the users who do use Angular as a tool in their company to help their product. Some major companies that use Angular commercially are:</p>
<ul>
<li>PayPal</li>
<li>Netflix</li>
<li>Lego</li>
<li>Lambda Test</li>
</ul>
<ol>
<li>License</li>
</ol>
<p>The Angular license closely follows the <a href="https://github.com/angular/angular/blob/master/LICENSE">MIT license</a>.</p>
<p>&nbsp;</p>
<h2>Stakeholders</h2>
<p>In a corporation, a stakeholder is a member of "groups without whose support the organization would cease to exist".<a href="https://tool.lu/markdown/#ref_sta1">[1]</a></p>
<p>As the definition above, stakeholders in Angular are interested in and influence Angular. More specifically, stakeholders can make a huge impact on Angular. Let's look at Angular's stakeholders, which include developers, maintainers, users, and other very important roles. After that we will have a deeper understanding and try to give the Power Interest Graph of Angular.</p>
<h3>Overview</h3>
<ul>
<li>Acquirers</li>
</ul>
<p>Acquirers, or called as investors, is the first part of the chain which decides the survival of tech companies. They are more concerned about the profit model of the product and the specific operation cost and market profit of the product. Angular's predecessor was Angular. AngularJS was born in 2009 and was created by&nbsp;<strong>Misko Hevery</strong>&nbsp;and others and later acquired by&nbsp;<strong>Google</strong>. Angular is built by a team of engineers who share a passion for making web development feel effortless, and now Angular is managed by them and their collaborators. Actually they are a large group of people, so we just list some of them.</p>
<p><img src="https://github.com/supercheerman/angular-1/tree/master/mypicture/2.png" alt="" /></p>
<p><em>Figure 1: Acquirers of Angular</em></p>
<ul>
<li>Developers</li>
</ul>
<p>As an open-source program on GitHub, dozens of developers would like to take part in this job. We can easily find them on GitHub. To make it clearer who contributed the most to Angular, here we list the contributors sorted by number of commits.</p>
<table>
<thead>
<tr>
<td>
<p><strong>Developer</strong></p>
</td>
<td>
<p><strong>Commits</strong></p>
</td>
<td>
<p><strong>Additions</strong></p>
</td>
<td>
<p><strong>Deletions</strong></p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td>
<p>@<a href="https://github.com/petebacondarwin">petebacondarwin</a></p>
</td>
<td>
<p>1120</p>
</td>
<td>
<p>406,538</p>
</td>
<td>
<p>247,475</p>
</td>
</tr>
<tr>
<td>
<p>@<a href="https://github.com/gkalpak">gkalpak</a></p>
</td>
<td>
<p>933</p>
</td>
<td>
<p>96,310</p>
</td>
<td>
<p>65,985</p>
</td>
</tr>
<tr>
<td>
<p>@<a href="https://github.com/vsavkin">vsavkin</a></p>
</td>
<td>
<p>952</p>
</td>
<td>
<p>165,431</p>
</td>
<td>
<p>117,393</p>
</td>
</tr>
<tr>
<td>
<p>@<a href="https://github.com/vicb">vicb</a></p>
</td>
<td>
<p>916</p>
</td>
<td>
<p>160,889</p>
</td>
<td>
<p>182,997</p>
</td>
</tr>
<tr>
<td>
<p>@<a href="https://github.com/IgorMinar">IgorMinar</a></p>
</td>
<td>
<p>856</p>
</td>
<td>
<p>244,201</p>
</td>
<td>
<p>221,320</p>
</td>
</tr>
</tbody>
</table>
<p><em>Table 1: Most contributed developers in trems of commit number</em></p>
<ul>
<li>Maintainers</li>
</ul>
<p>Maintainers are responsible for managing the development and evolution of Angular. They discuss the development direction of Angular. What&rsquo;s more, they accept and review pull-requests. We can view the main contributors on GitHub. They are the same as the Developers above.</p>
<ul>
<li>Users</li>
</ul>
<p>Angular is an MVVM framework used by&nbsp;<strong>Google</strong>&nbsp;and other front-end engineers in major projects.</p>
<ul>
<li>Suppliers</li>
</ul>
<p><strong>GitHub</strong>&nbsp;can be regarded as the supplier of Angular owing to it coordinated the process of Angular&rsquo;s development. Besides,&nbsp;<strong>JavaScript</strong>&nbsp;is the language of Angular, which can be also considered as the supplier.</p>
<ul>
<li>Communicators</li>
</ul>
<p>Angular has some large communities on&nbsp;<strong>GitHub</strong>,&nbsp;<strong>Gitter</strong>，<strong>Stack Overflow</strong>&nbsp;and so on. Every stakeholder of Angular can get help and find more about Angular here.</p>
<ul>
<li>Competitors</li>
</ul>
<p>Obviously, there are a lot of companies which also engaged in front-end development, such as&nbsp;<strong>Vue</strong>&nbsp;and&nbsp;<strong>React</strong>.</p>
<h3>Power Interest Grid</h3>
<p>The following figure shows the Power Interest Grid. Power Interest Grid contains the main stakeholder categories and more detailed explanation will be listed.</p>
<p><img src="https://github.com/supercheerman/angular-1/tree/master/mypicture/3.png" alt="" /></p>
<p><em>Figure 2: Power Interest Grid</em></p>
<ul>
<li>Low power and low interest</li>
</ul>
<p>Users, GitHub are stakeholders who do not has any control over Angular, and do not have significant roles in the development of Angular.</p>
<ul>
<li>Low power and high interest</li>
</ul>
<p>GitHub is the supplier of Angular and follow the latest development of Angular. Besides, the communities of Angular on GitHub, Gitter and Stake Overflow are the communicators. They are active in the discussion of Angular, but they do not have significant power to directly change the Angular. What&rsquo;s more, the Competitors of Angular will be greatly affected by the changes in Angular, but they have nearly no power to influence it.</p>
<ul>
<li>High power and low interest</li>
</ul>
<p>JavaScript are stakeholders who directly affect the development of Angular because JavaScript is the language Angular uses. But JavaScript won&rsquo;t pay attention on Angular.</p>
<ul>
<li>High power and high interest</li>
</ul>
<p>Core developers, maintainers and acquirers have significant interest and power in developing Angular.</p>
<h2>Development view</h2>
<p>Angular JS is not just a class library, but a complete framework. Angular is an MVC framework that provides you with many API functions. You can achieve more complex effects without writing many native js, such as animation, $. animate. It avoids you interacting with multiple class libraries and requires familiarity with the tedious work of multiple interfaces. It is designed by Google Chrome developers and leads the next generation of Web application development. Maybe we won't use Angular JS in five or 10 years, but its design essence will continue to be used.</p>
<p>Knowing the developers of Angular JS, you're sure to be excited about the ability of Angular JS custom instructions (which function like custom controls on the. NET platform). Custom instructions allow you to extend HTML tags and features. Instructions can be reused and used across projects. Large Web projects can be created using Angular JS. You can split the project into multiple modules and one module into multiple module files. At the same time, you can organize these documents according to your usage habits.</p>
<p><strong>&nbsp;</strong></p>
<p><strong>Main Components of Angular</strong></p>
<p>Modules</p>
<p>Templetes</p>
<p>Directives</p>
<p>Components</p>
<p>Data Binding</p>
<p>Dependency Injection&nbsp;</p>
<p>Metadata</p>
<p>Services</p>
<p><strong>&nbsp;</strong></p>
<p><strong>The characteristics of Angular</strong></p>
<p><strong>Two-way binding of data </strong></p>
<p>This is probably the most exciting feature. The data of view layer and model layer are two-way binding. One of them changes and the other changes accordingly. You don't need to write any code.</p>
<p>&nbsp;</p>
<p><strong>Code modularization</strong></p>
<p>Each module has its own scope, model, controller and so on.</p>
<p>&nbsp;</p>
<p><strong>Powerful directive</strong></p>
<p>It can encapsulate many functions into tags, attributes or annotations of HTML, which greatly beautifies the structure of HTML and enhances readability.</p>
<p>&nbsp;</p>
<p><strong>Dependency injection</strong></p>
<p>It gives the design pattern of the back-end language to the front-end code, which means that the front-end code can improve reusability and flexibility. The future model may put a large number of operations on the client side, and the service side only provides data sources and other operations that the client can not complete.</p>
<p>&nbsp;</p>
<p><strong>Test-driven development</strong></p>
<p>This is the goal of angular JS from the beginning. The application developed by angular can easily carry out unit testing and end-to-end testing, which solves the shortcomings of traditional JS code that is difficult to test and maintain.</p>
<p>&nbsp;</p>
<p><strong>Operating process</strong></p>
<p>The operation of angular is to implement a set of environments in JavaScript context, called angular context, and the non-angular environment is called classic context.</p>
<p>There is also a queue in the angular context, which contains the watch list, which contains the monitored variables, including those that bind to the data (that is, those that bind to the view). If the user changes a view that binds the data, then an angular function, $apply, is triggered (that is, putting the event queue in the event queue, and then triggering it when the training turns to this), and then updating the value of the change to the bound variable, and then starting to call a digest function, which is used to rotate the watch list to see the column. Table refers to whether or not to change, if there are changes to rewrite the corresponding DOM (do not need angular to write this part of the code, if you have 100 variables, you have to write 100 such changes, and if there are any changes in the future, you have to reconstruct it yourself).</p>
<p><img src="https://github.com/supercheerman/angular-1/tree/master/mypicture/3.png" alt="" /></p>
<h2>References</h2>
<p>[1]Wikipedia. Stakeholder (corporate)[EB/OL］.Stakeholder (corporate) - Wikipedia，<a href="http://wikipedia.moesalih.com/Stakeholder_(corporate)">http://wikipedia.moesalih.com/Stakeholder_(corporate)</a></p>
<p><a href="https://www.imooc.com/article/29750">https://www.imooc.com/article/29750</a></p>
<p><a href="https://www.jianshu.com/p/aa2446510c97">https://www.jianshu.com/p/aa2446510c97</a></p>
<p><a href="https://www.cnblogs.com/airen123/p/9479399.html">https://www.cnblogs.com/airen123/p/9479399.html</a></p>
<p><a href="https://blog.csdn.net/Mr_xiaoshulin/article/details/86029436">https://blog.csdn.net/Mr_xiaoshulin/article/details/86029436</a></p>
