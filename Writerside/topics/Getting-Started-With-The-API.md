# Getting Started With The API

To start, you need to add CustomNPCs as a dependency in your dependency manager.

<tabs>
<tab title="Maven">
Add the repository to the `repositories` section in your `pom.xml`
<code-block lang="XML">
&lt;repository&gt;
  &lt;id&gt;customnpcs&lt;/id&gt;
  &lt;name&gt;Foxikle's Repository&lt;/name&gt;
  &lt;url&gt;https://repo.foxikle.dev/public&lt;/url&gt;
&lt;/repository&gt;
</code-block>


Then, add the dependency to your dependencies section
<code-block lang="xml">
&lt;dependency&gt;
  &lt;groupId&gt;dev.foxikle&lt;/groupId&gt;
  &lt;artifactId&gt;customnpcs&lt;/artifactId&gt;
  &lt;version&gt;1.7&lt;/version&gt;
&lt;/dependency&gt;
</code-block>
</tab>
<tab title="Gradle (kotlin)">

Add the CustomNPCs Maven Repository

<code-block lang="kotlin">
maven {
    name = "foxiklePublic"
    url = uri("https://repo.foxikle.dev/public")
}
</code-block>
 OR
<code-block lang="kotlin">
maven ("https://repo.foxikle.dev/public")
</code-block>


<br>

Then, add the dependency to your `build.gradle.kts`
<code-block lang="KOTLIN">
compileOnly("dev.foxikle:customnpcs:1.7")

</code-block>

</tab>
<tab title="Gradle (Groovy)">

Add the CustomNPCs Maven Repository

<code-block lang="groovy">
maven {
    name "customnpcs"
    url "https://repo.foxikle.dev/public"
}

</code-block>

Add the dependency to your `build.gradle`
 <code-block lang="groovy">
compileOnly "dev.foxikle:customnpcs:1.7"

</code-block>
</tab>
</tabs>


Then, you can reload your project and get ready to use the API!

