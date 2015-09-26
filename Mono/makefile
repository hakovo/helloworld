# HelloWorld Makefile

all: HelloMono HelloForm TlsTest


HelloMono: HelloMono.cs
	mcs HelloMono.cs -out:bin/HelloMono.exe


TlsTest: TlsTest.cs
	mcs TlsTest.cs -out:bin/TlsTest.exe /r:System.dll /r:Mono.Security.dll


HelloForm: HelloForm.cs
	mcs HelloForm.cs -out:bin/HelloForm.exe -pkg:dotnet


clean:
	rm bin/*exe;
