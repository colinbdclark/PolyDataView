PolyDataView: a better polyfill for DataView
============================================

PolyDataView is a browser polyfill for [DataView](http://www.khronos.org/registry/typedarray/specs/latest/#8), 
part of the Khronos Typed Array specification. It is about twice as fast as other DataView polyfills out 
there, and has zero dependencies.

PolyDataView implements additional methods and behaviour that aren't included in the spec, but 
they are clearly labelled as such in the source code.

PolyDataView was written by Colin Clark and is distributed under the MIT and GPL licenses.

Contributions
-------------
 * getFloat32() and getFloat64() are modified from Christopher Chedeau's jDataView (https://github.com/vjeux/jDataView) 
 * getFloat80() is a modified version of Joe Turner's "extended" float decoder in Audiofile.js (https://github.com/oampo/audiofile.js/blob/master/audiofile.js)
 