# C++11 Notes

## New Features

### auto

Tell the compiler to automatically deduce the type of a variable

```
std::vector<int> MyArray
for(auto Iter : MyArray)
{
  // Iter is of type std::vector<int>::iterator (or is it const_iterator ?...)
}
```

### decltype

A type declaration which references another type declaration... 'use the type of this...'

