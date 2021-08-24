## .NET Framework - <a name=".netframework"></a>

.NET is a framework to develop software applications. It is designed and developed by Microsoft and the first beta version released in 2000.

It is used to develop applications for web, Windows, phone. Moreover, it provides a broad range of functionalities and support.

This framework contains a large number of class libraries known as Framework Class Library (FCL). The software programs written in .NET are executed in the execution environment, which is called CLR (Common Language Runtime). These are the core and essential parts of the .NET framework.

This framework provides various services like memory management, networking, security, memory management, and type-safety.

The .Net Framework supports more than 60 programming languages such as C#, F#, VB.NET, J#, VC++, JScript.NET, APL, COBOL, Perl, Oberon, ML, Pascal, Eiffel, Smalltalk, Python, Cobra, ADA, etc.

Following is the .NET framework Stack that shows the modules and components of the Framework.

The .NET Framework is composed of four main components:

- Common Language Runtime (CLR)
- Framework Class Library (FCL),
- Core Languages (WinForms, ASP.NET, and ADO.NET), and
- Other Modules (WCF, WPF, WF, Card Space, LINQ, Entity Framework, Parallel LINQ, Task Parallel Library, etc.)

    
![Componants of .Net Framework](https://static.javatpoint.com/csharp/net/images/net-framework.png)

---
> **1) CLR (Common Language Runtime) :**<a name="clr"></a>

It is a program execution engine that loads and executes the program. It converts the program into native code. It acts as an interface between the framework and operating system. It does exception handling, memory management, and garbage collection. Moreover, it provides security, type-safety, interoperability, and portablility. A list of CLR components are given below:

![CLR](https://static.javatpoint.com/csharp/net/images/net-common-language-runtime.png)

**.NET CLR Functions :**

Following are the functions of the CLR.

1. It converts the program into native code.
2. Handles Exceptions
3. Provides type-safety
4. Memory management
5. Provides security
6. Improved performance
7. Language independent
8. Platform independent
9. Garbage collection
10. Provides language features such as inheritance, interfaces, and overloading for object-oriented programmings.

**.NET CLR Versions :**

The CLR updates itself time to time to provide better performance.

.NET version | CLR versions
--- | ---
1.0	| 1.0
1.1	| 1.1
2.0	| 2.0
3.0	| 2.0
3.5	| 2.0
4 | 4
4.5 | 4
4.6 | 4
4.6 | 4

**Base Class Library Support :**

It is a class library that provides support of classes to the .NET application.

**Thread Support :**

It manages the parallel execution of the multi-threaded application.

**COM Marshaler :**

It provides communication between the COM objects and the application.

**Type Checker :**

It checks types used in the application and verifies that they match to the standards provided by the CLR.

**Code Manager :**

It manages code at execution run-time.

**Garbage Collector :**

It releases the unused memory and allocates it to a new application.

**ClassLoader :**

It is used to load all classes at run time.

---
> **2) FCL (Framework Class Library) :**<a name="fcl"></a>

It is a standard library that is a collection of thousands of classes and used to build an application. The BCL (Base Class Library) is the core of the FCL and provides basic functionalities.

![FCl](https://static.javatpoint.com/csharp/net/images/net-framework-base-class-library.png)

It contains thousands of classes that supports the following functions.

- Base and user-defined data types
- Support for exceptions handling
- input/output and stream operations
- Communications with the underlying system
- Access to data
- Ability to create Windows-based GUI applications
- Ability to create web-client and server applications
- Support for creating web services

**.NET Framework Class Library Namespaces :**

Following are the commonly used namespaces that contains useful classes and interfaces and defined in Framework Class Library.

Namespaces	| Description
---------- | --------------
System	| It includes all common datatypes, string values, arrays and methods for data conversion.
System.Data, System.Data.Common, System.Data.OleDb, System.Data.SqlClient, System.Data.SqlTypes | These are used to access a database, perform commands on a database and retrieve database.
System.IO, System.DirectoryServices, System.IO.IsolatedStorage |	These are used to access, read and write files.
System.Diagnostics	| It is used to debug and trace the execution of an application.
System.Net, System.Net.Sockets	| These are used to communicate over the Internet when creating peer-to-peer applications.
System.Windows.Forms, System.Windows.Forms.Design	| These namespaces are used to create Windows-based applications using Windows user interface components.
System.Web, System.WebCaching, System.Web.UI, System.Web.UI.Design, System.Web.UI.WebControls, System.Web.UI.HtmlControls, System.Web.Configuration, System.Web.Hosting, System.Web.Mail, System.Web.SessionState	| These are used to create ASP. NET Web applications that run over the web.
System.Web.Services, System.Web.Services.Description, System.Web.Services.Configuration, System.Web.Services.Discovery, System.Web.Services.Protocols	| These are used to create XML Web services and components that can be published over the web.
System.Security, System.Security.Permissions, System.Security.Policy, System.WebSecurity, System.Security.Cryptography	| These are used for authentication, authorization, and encryption purpose.
System.Xml, System.Xml.Schema, System.Xml.Serialization, System.Xml.XPath, System.Xml.Xsl	| These namespaces are used to create and access XML files.

---
> **3. Core Languages :**<a name="cl"></a>
### 3.1 WinForms -
Windows Forms is a smart client technology for the .NET Framework, a set of managed libraries that simplify common application tasks such as reading and writing to the file system.

### 3.2 ASP.NET -
ASP.NET is a web framework designed and developed by Microsoft. It is used to develop websites, web applications, and web services. It provides a fantastic integration of HTML, CSS, and JavaScript. It was first released in January 2002.

### 3.3 ADO.NET -
ADO.NET is a module of .Net Framework, which is used to establish a connection between application and data sources. Data sources can be such as SQL Server and XML. ADO .NET consists of classes that can be used to connect, retrieve, insert, and delete data.

---
> **4. Other Modules :**<a name="other_modules"></a>
### 4.1 WPF (Windows Presentation Foundation) -
Windows Presentation Foundation (WPF) is a graphical subsystem by Microsoft for rendering user interfaces in Windows-based applications. WPF, previously known as "Avalon", was initially released as part of .NET Framework 3.0 in 2006. WPF uses DirectX.

### 4.2 WCF (Windows Communication Foundation) -
It is a framework for building service-oriented applications. Using WCF, you can send data as asynchronous messages from one service endpoint to another.

### 4.3 WF (Workflow Foundation) -
Windows Workflow Foundation (WF) is a Microsoft technology that provides an API, an in-process workflow engine, and a rehostable designer to implement long-running processes as workflows within .NET applications.

### 4.4 LINQ (Language Integrated Query) -
It is a query language, introduced in .NET 3.5 framework. It is used to make the query for data sources with C# or Visual Basics programming languages.

### 4.5 Entity Framework -
It is an ORM based open source framework which is used to work with a database using .NET objects. It eliminates a lot of developers effort to handle the database. It is Microsoft's recommended technology to deal with the database.

### 4.6 Parallel LINQ -
Parallel LINQ or PLINQ is a parallel implementation of LINQ to objects. It combines the simplicity and readability of LINQ and provides the power of parallel programming.

It can improve and provide fast speed to execute the LINQ query by using all available computer capabilities.

Apart from the above features and libraries, .NET includes other APIs and Model to improve and enhance the .NET framework.

In 2015, Task parallel and Task parallel libraries were added. In .NET 4.5, a task-based asynchronous model was added.
