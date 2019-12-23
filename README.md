# elastic-kibana
elastic-kibana 

An Example about how to add logging from an MVC Controller
Since we specified that we want to log messages with a log level of information or higher, 
a number of information messages were logged by default.
But what if we want to log our own messages? Thankfully, this is pretty easy to do. It 'll log a message in the HomeController.

Traditionally, logging required a lot of upfront work to get up and running. As such, logging is usually left out entirely or 
it's written to some obscure text file on a server that is difficult to access.

ElasticSearch and Kibana changed all of that. ElasticSearch and Kibana up 
and running with no effort required. When you think about the powerful functionality that ElasticSearch and Kibana offers, 
and how performant it is, it's really quite impressive especially considering that it's open source.

Even without plugins like Serilog, logging has become a lot easier in ASP.NET Core compared to ASP.NET, so kudos to the
.NET Core team for making an extensible logging framework. Serilog simply built on top of this and extended this functionality 
by making logging for .NET Core developers an even simpler process.

When you think about all the convenience and functionality you get by ElasticSearch, Kibana, ASP.NET Core and Serilog,
there's really no excuse for developers to not incorporate logging into applications anymore.
