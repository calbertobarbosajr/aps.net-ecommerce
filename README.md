<h1>Project Documentation</h1>
<h2>eCommerce ASP.NET Core MVC</h2>
<p>This project was created based on what I learned in the Udemy course "ASP.NET CORE MVC | Build a Complete eCommerce App." The course is taught by Ervis Trupja, and it is available <a href="https://www.udemy.com/course/complete-ecommerce-aspnet-mvc-application/?utm_source=adwords&amp;utm_medium=udemyads&amp;utm_campaign=WebDevelopment_v.PROF_la.EN_cc.BR_ti.8322&amp;utm_content=deal4584&amp;utm_term=_._ag_108455848694_._ad_467154447027_._kw__._de_c_._dm__._pl__._ti_dsa-774930035449_._li_1001655_._pd__._&amp;matchtype=&amp;gad_source=1&amp;gclid=EAIaIQobChMIl4Lr0PioggMVoRNlCh3_VwOXEAAYASAAEgJOifD_BwE" target="_new">here</a>.</p>
<h2>Description</h2>
<p>This project is an ASP.NET Core MVC-based eCommerce application that uses an SQL database and Entity Framework to store and manage data. It also includes PayPal payment integration, cookie-based authentication, and role-based user interface rendering.</p>
<h2>Key Features</h2>
<ul>
<li>
<p><strong>Models vs. ViewModels</strong>: The project distinguishes between models and ViewModels to better represent data and user interface needs.</p>
</li>
<li>
<p><strong>Views vs. PartialViews</strong>: Use of Views and PartialViews to create a consistent and dynamic user experience.</p>
</li>
<li>
<p><strong>SQL Server Configuration with Entity Framework</strong>: The SQL database is configured and managed with Entity Framework.</p>
</li>
<li>
<p><strong>Entity Framework Migrations</strong>: Use of Entity Framework migrations to track changes in the database schema.</p>
</li>
<li>
<p><strong>CRUD Operations with Entity Framework</strong>: Addition, querying, updating, and deletion of data from the SQL database using Entity Framework.</p>
</li>
<li>
<p><strong>Working with Relational and Non-Relational Data</strong>: In addition to SQL, the project also demonstrates working with relational and non-relational data.</p>
</li>
<li>
<p><strong>Dependency Injection</strong>: Use of dependency injection to keep the code decoupled and easy to test.</p>
</li>
<li>
<p><strong>Dependency Lifetimes</strong>: Management of dependencies with different lifetimes such as Singleton, Transient, and Scoped.</p>
</li>
<li>
<p><strong>Generic Services/Repositories</strong>: Implementation of generic services and repositories for common tasks like creating, reading, updating, and deleting data.</p>
</li>
<li>
<p><strong>Model Binding and Validation</strong>: Use of model binding and validation to ensure data integrity.</p>
</li>
<li>
<p><strong>Routing</strong>: Configuration of routing to direct requests to the appropriate controllers.</p>
</li>
<li>
<p><strong>Cookie-Based Authentication</strong>: Implementation of cookie-based authentication to secure restricted areas of the application.</p>
</li>
<li>
<p><strong>Role-Based Authorization</strong>: Use of role-based authorization to control access to different parts of the application.</p>
</li>
<li>
<p><strong>Role-Based UI Rendering</strong>: Dynamic display of user interface elements based on user roles.</p>
</li>
<li>
<p><strong>Dynamic Rendering with ViewComponents</strong>: Use of ViewComponents to efficiently render dynamic content.</p>
</li>
<li>
<p><strong>Online Payments with PayPal SDK</strong>: Integration of the PayPal SDK to accept online payments.</p>
</li>
</ul>
<h2>Required Dependencies</h2>
<p>Make sure to install the following dependencies before running the project:</p>
<ul>
<li>Microsoft.AspNetCore.Identity</li>
<li>Microsoft.EntityFrameworkCore</li>
<li>Microsoft.EntityFrameworkCore.Design</li>
<li>Microsoft.EntityFrameworkCore.SqlServer</li>
<li>Microsoft.EntityFrameworkCore.Tools</li>
<li>Microsoft.AspNetCore.Authentication.Cookies</li>
<li>Microsoft.AspNetCore.Identity.EntityFrameworkCore --version 7.0.13</li>
</ul>
<p>Additionally, install the Entity Framework tool with the following commands:</p>
<p><code>dotnet tool uninstall --global dotnet-ef</code><br /><code>dotnet tool install --global dotnet-ef</code></p>
<p>After installing the dependencies, run the Entity Framework migrations and update the database with the following commands:</p>
<p><code>dotnet ef migrations add Initial</code><br /><code>dotnet ef database update</code></p>
<h2>Running the Project</h2>
<p>To run the project, follow these steps:</p>
<ol>
<li>Clone this repository to your local machine.</li>
<li>Ensure you have all dependencies installed as mentioned above.</li>
<li>Configure the database settings in the <code>appsettings.json</code> file.</li>
<li>Open the terminal in the project folder and run <code>dotnet run</code>.</li>
<li>Access the application in your web browser at <a href="http://localhost:5000/" target="_new">http://localhost:5000</a>.</li>
</ol>
<h2>Contributions</h2>
<p>Contributions are welcome! Feel free to open issues, propose improvements, and collaborate on this project.</p>
<h2>License</h2>
<p>This project is licensed under the <a href="https://opensource.org/license/mit/" target="_new">MIT License</a>.</p>
