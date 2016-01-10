Rantionary
=========

This is the official dictionary for use with [Rant](http://github.com/TheBerkin/Rant).

**Contributions are welcome.** I love new words! If you want to add something, be it big or small, send a pull request and I'll get to it within a couple days at the most.

To learn the Rant dictionary file format, see [this article](http://github.com/TheBerkin/Rant/wiki/Dictionary-format).

**Note:** These dictionaries contain potentially objectionable content. Such entries should *always* be placed under a `#nsfw` context. Rant will exclude these entries by default when loading vocabulary, but if you want to include them, specify `NsfwFilter.Allow` in your `RantEngine` constructor.

*These files are made available publicly without license or restriction. Use them in any way you wish.*

This is the official dictionary for use with [Rant](http://github.com/TheBerkin/Rant).

The latest .rantpkg build can be downloaded from [AppVeyor](https://ci.appveyor.com/project/TheBerkin/rantionary-4x1ls/build/artifacts).

##Resources

To learn the Rant dictionary file format, see [the official Rant dictionary guide](https://github.com/RantLang/DictionaryGuide).

Some tables use Diffmark to save space and make entries more readable. Read about Diffmark [here](https://github.com/TheBerkin/Diffmark/blob/master/README.md).

##Contribute

**Contributions are welcome.** I love new words! If you want to add something, be it big or small, send a pull request and I'll get to it within a couple days at the most.

##NSFW content

These dictionaries contain potentially objectionable content. Such entries should *always* be placed under a `nsfw` class. Rant will hide this class by default when loading dictionaries, but if you want to include them in queries without an explicit filter, do either of the following:
```cs
// From RantDictionary
myDictionary.IncludeHiddenClass("nsfw");

// From RantEngine
engine.Dictionary.IncludeHiddenClass("nsfw");
```

##License (or lack thereof)

These files are made available publicly without license or restriction. Use them in any way you wish.
