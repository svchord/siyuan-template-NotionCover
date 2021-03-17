{{ $coverPath := nospace (cat "https://picsum.photos/id/" ((randInt 1 719) | toString) "/1600/500")}}

![Cover]({{$coverPath}})