<p>How to install and work with Angular 2</p>
<p>Angular 2 is an open source JavaScript Framework to build Web and Mobile applications in HTML and JavaScript.</p>
<p>To start work with Angular 2. You should be familiar with the basics of HTML, CSS, and JavaScript before starting the Angular 2.</p>
<p>To install before the Angular. You need to install Node Package Manager (NPM). You can install NPM from the official site <a href="https://www.npmjs.com">https://www.npmjs.com</a></p>
<p>Now you need to create a folder where you want to create the Angular 2 App.</p>
<p>Now you can install Angular 2 with Angular command Line Interface (CLI). To install Angular with CLI you need to open the command prompt in same folder which you create and run this command</p>
<pre>
	<code>  		npm install -g angular-cli 	</code>
</pre>
<p>As soon command install and download all the CLI component then you need to run another command to create the project.</p>
<pre>
	<code> 		ng new angular2Demo 	</code>
</pre>
<p>Here <code>ng new </code> is the cli command to create the new project and angular2Demo is the name of project.</p>
<p>As you run the above command. A new project folder will create with the same name as you provide &quot;angular2Demo&quot; and following directory structure.</p>
<pre>
	<code>  		angular2Demo/ 	 		e2e/ 	 		node_modules/ 	 		src/ 		 		app/ 			 		app.component.css 			 		app.component.html 			 		app.component.spec.ts 			 		app.component.ts 			 		app.module.ts 		 		assets/ 		 		environments/ 		 		favicon.ico 		 		index.html 		 		main.ts 		 		polyfills.ts 		 		style.css 		 		test.ts 		 		tsconfig.app.json 		 		tsconfig.spec.json 		 		typings.d.ts 	 		.angular-cli.json 	 		.editorconfig 	 		.gitignore 	 		karma.conf 	 		package.json 	 		protractor.conf 	 		README.md 	 		tsconfig.json 	 		tslint.json  	</code>
</pre>
<p>So this is the directory structure</p>
<p>To run this project you need to run the command on Command prompt.</p>
<pre>
 	ng serve 
</pre>
<p>As you run this command your application will run and you can browse it on <a href="http://localhost:4200">http://localhost:4200</a> by default Angular 2 Apps runs on 4200 port.</p>
<p>Now you can modify your app. For modifying the app you need to changes in the following files.</p>
<p><code>app.component.html</code></p>
<pre>
	<code> app works! </code>
</pre>
<p><code>app.component.ts</code></p>
<pre>
	<code>  		import { Component } from '@angular/core';   		 		@Component({    			selector: 'app-root',    			templateUrl: './app.component.html',    			styleUrls: ['./app.component.css']  		})   		export class AppComponent {    			title = 'Angular 2 Demo App';  		}  	</code>
</pre>
<p><code>app.module.ts</code></p>
<pre>
	<code>  		import { BrowserModule } from '@angular/platform-browser';  		import { NgModule } from '@angular/core';   		import { AppComponent } from './app.component';    		@NgModule({    			declarations: [ AppComponent ],    			imports: [ BrowserModule ],    			providers: [],    			bootstrap: [AppComponent]  		})   		export class AppModule { }  	</code>
</pre>
<p>So you can changes in these files to make modification in app.</p>
<p>You can find this app on my GitHub site <a href="https://github.com/eranilkapoor/angular2-demo-app">https://github.com/eranilkapoor/angular2-demo-app</a></p>
