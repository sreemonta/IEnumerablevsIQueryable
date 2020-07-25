# IEnumerablevsIQueryable
Initial commit

# How do they work
1 (a). IEnumerable exist in the System.Collection.Namespace
1 (b). IQueryable exists in the System.Linq Namespace
2 (a). IEnumerable is suitable for querying data from in-memory collections like List, Array and so on.
2 (b). IQueryable is suitable for querying data from out-memory (like remote database, service) collections.
3 (a). While querying data from the database, IEnumerable executes "select query" on the server-side, loads data in-memory on the client-side and then filters the data.
3 (b). While querying data from a database, IQueryable executes a "select query" on server-side with all filters.

