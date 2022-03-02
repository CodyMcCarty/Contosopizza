# Contoso Pizza
This was created using the MS Learn tut.  https://docs.microsoft.com/en-us/learn/paths/build-dotnet-applications-csharp/

## Usage
run `dotnet run` to start the API.  This will also give you the ports used.  
may need to run `dotnet buld` if it fails.  
Go to `https://localhost:7240/pizza` replace 7240 with your port to view in a webpage to see the pizzas.  
run `httprepl https://localhost:7240` (replace 7240 with your port) in a new terminal.  This will start a repl.  Commands such as cd and ls work as expected.  ls will also list CRUD.   
1. get: `get`
1. getID: `get 2`
1. post: `post -c "{"name":"Hawaii", "isGlutenFree":false}"`
1. put: `put 3 -c  "{"id": 3, "name":"Hawaiian", "isGlutenFree":false}"`
1. delete: `delete 3`

