# Simple dotnetcore app

Install .Netcore:

https://www.microsoft.com/net/core#macos

http://www.hanselman.com/blog/SelfcontainedNETCoreApplications.aspx

This gives a better intro

https://blogs.msdn.microsoft.com/luisdem/2016/10/11/net-core-how-to-publish-a-self-contained-application-exe/

# Running

    dotnet restore
    dotnet build
    dotnet publish -c release
    bin/release/netcoreapp1.1/osx.10.11-x64/dotnetcore

Should output

    $ bin/release/netcoreapp1.1/osx.10.11-x64/dotnetcore
    Hello World!

