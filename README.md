## <a href="https://github.com/bineeg/Bambda/blob/main/GraphQL/GraphQLScoper.bambda">GraphQLScoper</a>

This script helps filter out GraphQL operations that have already been tested. Since all GraphQL requests use the same endpoint, traditional URI-based scoping in Burp is not effective for distinguishing operations. With this Bambda script, you can automatically exclude previously tested GraphQL queries or mutations, reducing noise in the HTTP history and focusing only on untested operations.
After importing the script, please manually update the in-scope, out-of-scope, and excluded operations values directly inside the script.
