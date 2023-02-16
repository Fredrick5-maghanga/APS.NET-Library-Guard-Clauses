Guard Clauses
A guard clause is a software pattern that simplifies complex functions by
 "failing fast", checking for invalid inputs up front and immediately failing if any are found.

Supported Guard Clauses
Guard.Against.Null (throws if input is null)
Guard.Against.NullOrEmpty (throws if string, guid or array input is null or empty)
Guard.Against.NullOrWhiteSpace (throws if string input is null, empty or whitespace)
Guard.Against.OutOfRange (throws if integer/DateTime/enum input is outside a provided range)
Guard.Against.EnumOutOfRange (throws if a enum value is outside a provided Enum range)
Guard.Against.OutOfSQLDateRange (throws if DateTime input is outside the valid range of SQL Server DateTime values)
Guard.Against.Zero (throws if number input is zero)
