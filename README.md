# JavaScript Null vs. Undefined in Length Property Access

This repository demonstrates a common JavaScript error related to handling null and undefined values when checking object properties, specifically the 'length' property.

The bug arises from the loose equality check (==) in the conditional statement of the 'foo' function. The solution addresses this by using strict equality (===) or using optional chaining.