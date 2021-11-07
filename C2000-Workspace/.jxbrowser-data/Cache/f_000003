(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function r(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
r("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
r("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){if(!(a instanceof Array)){a=u(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ja;
if("function"==typeof Object.setPrototypeOf)ja=Object.setPrototypeOf;else{var ka;a:{var la={a:!0},ma={};try{ma.__proto__=la;ka=ma.a;break a}catch(a){}ka=!1}ja=ka?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var na=ja;
function v(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(na)na(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.S=b.prototype}
function oa(){this.o=!1;this.l=null;this.i=void 0;this.h=1;this.u=this.m=0;this.F=this.j=null}
function pa(a){if(a.o)throw new TypeError("Generator is already running");a.o=!0}
oa.prototype.B=function(a){this.i=a};
function qa(a,b){a.j={hb:b,jb:!0};a.h=a.m||a.u}
oa.prototype.return=function(a){this.j={return:a};this.h=this.u};
function w(a,b,c){a.h=c;return{value:b}}
oa.prototype.A=function(a){this.h=a};
function ra(a,b,c){a.m=b;void 0!=c&&(a.u=c)}
function sa(a){a.m=0;var b=a.j.hb;a.j=null;return b}
function ta(a){a.F=[a.j];a.m=0;a.u=0}
function ua(a){var b=a.F.splice(0)[0];(b=a.j=a.j||b)?b.jb?a.h=a.m||a.u:void 0!=b.A&&a.u<b.A?(a.h=b.A,a.j=null):a.h=a.u:a.h=0}
function va(a){this.h=new oa;this.i=a}
function wa(a,b){pa(a.h);var c=a.h.l;if(c)return xa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return ya(a)}
function xa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.o=!1,e;var f=e.value}catch(g){return a.h.l=null,qa(a.h,g),ya(a)}a.h.l=null;d.call(a.h,f);return ya(a)}
function ya(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.o=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,qa(a.h,c)}a.h.o=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.jb)throw b.hb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Aa(a){this.next=function(b){pa(a.h);a.h.l?b=xa(a,a.h.l.next,b,a.h.B):(a.h.B(b),b=ya(a));return b};
this.throw=function(b){pa(a.h);a.h.l?b=xa(a,a.h.l["throw"],b,a.h.B):(qa(a.h,b),b=ya(a));return b};
this.return=function(b){return wa(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ca(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ca(new Aa(new va(a)))}
function Da(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
r("Reflect",function(a){return a?a:{}});
r("Reflect.construct",function(){return ia});
r("Reflect.setPrototypeOf",function(a){return a?a:na?function(b,c){try{return na(b,c),!0}catch(d){return!1}}:null});
r("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.o=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.u()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.u=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.R),reject:g(this.u)}};
b.prototype.R=function(g){if(g===this)this.u(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ka(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.N(g):this.m(g)}};
b.prototype.N=function(g){var h=void 0;try{h=g.then}catch(k){this.u(k);return}"function"==typeof h?this.la(h,g):this.m(g)};
b.prototype.u=function(g){this.B(2,g)};
b.prototype.m=function(g){this.B(1,g)};
b.prototype.B=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Y();this.F()};
b.prototype.Y=function(){var g=this;e(function(){if(g.H()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.H=function(){if(this.o)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.F=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ka=function(g){var h=this.l();g.ya(h.resolve,h.reject)};
b.prototype.la=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,q){return"function"==typeof t?function(z){try{l(t(z))}catch(A){n(A)}}:q}
var l,n,p=new b(function(t,q){l=t;n=q});
this.ya(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.ya=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.o=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),n=l.next();!n.done;n=l.next())d(n.value).ya(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(z){return function(A){t[z]=A;q--;0==q&&l(t)}}
var t=[],q=0;do t.push(void 0),q++,d(k.value).ya(p(t.length-1),n),k=h.next();while(!k.done)})};
return b});
function Ea(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
r("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ea(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ea(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Ea(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Ea(k,g)&&Ea(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Ea(k,g)&&Ea(k[g],this.h)?delete k[g][this.h]:!1};
return b});
r("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ea(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Ea(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Fa(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
r("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Fa(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
r("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
r("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Fa(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
function Ga(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
r("Array.prototype.entries",function(a){return a?a:function(){return Ga(this,function(b,c){return[b,c]})}});
r("Object.setPrototypeOf",function(a){return a||na});
var Ha="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ea(d,e)&&(a[e]=d[e])}return a};
r("Object.assign",function(a){return a||Ha});
r("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
r("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ea(b,d)&&c.push([d,b[d]]);return c}});
r("Array.prototype.keys",function(a){return a?a:function(){return Ga(this,function(b){return b})}});
r("Array.prototype.values",function(a){return a?a:function(){return Ga(this,function(b,c){return c})}});
r("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
r("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
r("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Fa(this,b,"includes").indexOf(b,c||0)}});
r("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
r("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
r("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
r("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)Ea(b,d)&&c.push(b[d]);return c}});
var y=this||self;function B(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function C(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ia(){}
function Ja(a){a.Ra=void 0;a.getInstance=function(){return a.Ra?a.Ra:a.Ra=new a}}
function Ka(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function La(a){var b=Ka(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Na(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Oa(a){return Object.prototype.hasOwnProperty.call(a,Pa)&&a[Pa]||(a[Pa]=++Qa)}
var Pa="closure_uid_"+(1E9*Math.random()>>>0),Qa=0;function Ra(a,b,c){return a.call.apply(a.bind,arguments)}
function Sa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ta(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ta=Ra:Ta=Sa;return Ta.apply(null,arguments)}
function Ua(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Va(a,b){B(a,b,void 0)}
function D(a,b){function c(){}
c.prototype=b.prototype;a.S=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Qm=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Wa(a){return a}
;function Xa(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Xa);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.wb=b)}
D(Xa,Error);Xa.prototype.name="CustomError";function Ya(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Za(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var $a=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},E=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},ab=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},bb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},cb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
E(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function db(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function eb(a,b){b=$a(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function fb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function gb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(La(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function hb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function ib(a){var b=jb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function kb(a){for(var b in a)return!1;return!0}
function lb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function mb(){var a=F("PLAYER_VARS",{});return null!==a&&"privembed"in a?a.privembed:!1}
function nb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function ob(a){var b={},c;for(c in a)b[c]=a[c];return b}
function pb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=pb(a[c]);return b}
var qb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function rb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<qb.length;f++)c=qb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var sb;function tb(){if(void 0===sb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Wa,createScript:Wa,createScriptURL:Wa})}catch(c){y.console&&y.console.error(c.message)}sb=a}else sb=a}return sb}
;function ub(a,b){this.h=a===vb&&b||""}
ub.prototype.ca=!0;ub.prototype.ba=function(){return this.h};
function wb(a){return new ub(vb,a)}
var vb={};wb("");var xb={};function yb(a){this.h=xb===xb?a:"";this.ca=!0}
yb.prototype.ba=function(){return this.h.toString()};
yb.prototype.toString=function(){return this.h.toString()};function zb(a,b){this.h=b===Ab?a:""}
m=zb.prototype;m.ca=!0;m.ba=function(){return this.h.toString()};
m.Pa=!0;m.La=function(){return 1};
m.toString=function(){return this.h+""};
function Bb(a){if(a instanceof zb&&a.constructor===zb)return a.h;Ka(a);return"type_error:TrustedResourceUrl"}
var Ab={};function Cb(a){var b=tb();a=b?b.createScriptURL(a):a;return new zb(a,Ab)}
;var Db=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Eb=/&/g,Fb=/</g,Gb=/>/g,Hb=/"/g,Ib=/'/g,Kb=/\x00/g,Lb=/[\x00&<>"']/;function Mb(a,b){this.h=b===Nb?a:""}
m=Mb.prototype;m.ca=!0;m.ba=function(){return this.h.toString()};
m.Pa=!0;m.La=function(){return 1};
m.toString=function(){return this.h.toString()};
function Ob(a){if(a instanceof Mb&&a.constructor===Mb)return a.h;Ka(a);return"type_error:SafeUrl"}
var Pb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),Qb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Rb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Nb={},Sb=new Mb("about:invalid#zClosurez",Nb);var Tb;a:{var Ub=y.navigator;if(Ub){var Vb=Ub.userAgent;if(Vb){Tb=Vb;break a}}Tb=""}function G(a){return-1!=Tb.indexOf(a)}
;function Wb(){return(G("Chrome")||G("CriOS"))&&!G("Edge")}
;var Xb={};function Yb(a,b,c){this.h=c===Xb?a:"";this.i=b;this.ca=this.Pa=!0}
Yb.prototype.La=function(){return this.i};
Yb.prototype.ba=function(){return this.h.toString()};
Yb.prototype.toString=function(){return this.h.toString()};
function Zb(a,b){var c=tb();a=c?c.createHTML(a):a;return new Yb(a,b,Xb)}
;function $b(a,b){b instanceof Mb||b instanceof Mb||(b="object"==typeof b&&b.ca?b.ba():String(b),Rb.test(b)||(b="about:invalid#zClosurez"),b=new Mb(b,Nb));a.href=Ob(b)}
function ac(a,b){a.rel="stylesheet";a.href=Bb(b).toString();(b=bc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function cc(){return bc("script[nonce]",void 0)}
var dc=/^[\w+/_-]+[=]{0,2}$/;function bc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&dc.test(a)?a:"":""}
;function ec(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var fc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function gc(a){return a?decodeURI(a):a}
function hc(a){return gc(a.match(fc)[3]||null)}
function ic(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)ic(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function jc(a){var b=[],c;for(c in a)ic(c,a[c],b);return b.join("&")}
function kc(a,b){b=jc(b);if(b){var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.substr(0,d),e,a.substr(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;b=a[0]+(a[1]?"?"+a[1]:"")+a[2]}else b=a;return b}
var lc=/#|$/;function mc(a){y.setTimeout(function(){throw a;},0)}
;function nc(){return G("iPhone")&&!G("iPod")&&!G("iPad")}
;function oc(a){oc[" "](a);return a}
oc[" "]=Ia;var pc=G("Opera"),qc=G("Trident")||G("MSIE"),rc=G("Edge"),sc=G("Gecko")&&!(-1!=Tb.toLowerCase().indexOf("webkit")&&!G("Edge"))&&!(G("Trident")||G("MSIE"))&&!G("Edge"),tc=-1!=Tb.toLowerCase().indexOf("webkit")&&!G("Edge"),uc=G("Android");function vc(){var a=y.document;return a?a.documentMode:void 0}
var wc;a:{var xc="",yc=function(){var a=Tb;if(sc)return/rv:([^\);]+)(\)|;)/.exec(a);if(rc)return/Edge\/([\d\.]+)/.exec(a);if(qc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(tc)return/WebKit\/(\S+)/.exec(a);if(pc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
yc&&(xc=yc?yc[1]:"");if(qc){var zc=vc();if(null!=zc&&zc>parseFloat(xc)){wc=String(zc);break a}}wc=xc}var Ac=wc,Bc;if(y.document&&qc){var Cc=vc();Bc=Cc?Cc:parseInt(Ac,10)||void 0}else Bc=void 0;var Dc=Bc;var Fc=nc()||G("iPod"),Gc=G("iPad");!G("Android")||Wb();Wb();var Hc=G("Safari")&&!(Wb()||G("Coast")||G("Opera")||G("Edge")||G("Edg/")||G("OPR")||G("Firefox")||G("FxiOS")||G("Silk")||G("Android"))&&!(nc()||G("iPad")||G("iPod"));var Ic={},Jc=null;
function Kc(a,b){La(a);void 0===b&&(b=0);if(!Jc){Jc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));Ic[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===Jc[h]&&(Jc[h]=g)}}}b=Ic[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var Lc="function"===typeof Uint8Array;var Mc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function Nc(a,b){Object.isFrozen(a)?Oc(a):Mc?a[Mc]|=b:void 0!==a.h?a.h|=b:Object.defineProperties(a,{h:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function Oc(a){var b;Mc?b=a[Mc]:b=a.h;return null==b?0:b}
function Pc(a){Nc(a,1);return a}
function Qc(a){return Array.isArray(a)?!!(Oc(a)&2):!1}
function Rc(a){if(!Array.isArray(a))throw Error("cannot mark non-array as immutable");Nc(a,2)}
;function Sc(a){return null!==a&&"object"===typeof a&&a.constructor===Object}
function Tc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":return Lc&&null!=a&&a instanceof Uint8Array?Kc(a):a;default:return a}}
;function Uc(a,b){if(null!=a)return Array.isArray(a)||Sc(a)?Vc(a,b):b(a)}
function Vc(a,b){if(Array.isArray(a)){for(var c=Array(a.length),d=0;d<a.length;d++)c[d]=Uc(a[d],b);Oc(a)&1&&Pc(c);return c}c={};for(d in a)c[d]=Uc(a[d],b);return c}
function Wc(a){return Lc&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;function Xc(a,b){this.h=a;this.i=b;this.map={};this.j=!0;if(0<this.h.length){for(a=0;a<this.h.length;a++){b=this.h[a];var c=b[0];this.map[c.toString()]=new Yc(c,b[1])}this.j=!0}}
m=Xc.prototype;m.toJSON=function(){var a=this.T();return Vc(a,Tc)};
m.T=function(){if(this.j){if(this.i){var a=this.map,b;for(b in a)if(Object.prototype.hasOwnProperty.call(a,b)){var c=a[b].h;c&&c.T()}}}else{this.h.length=0;a=Zc(this);a.sort();for(b=0;b<a.length;b++){c=this.map[a[b]];var d=c.h;d&&d.T();this.h.push([c.key,c.value])}this.j=!0}return this.h};
m.clear=function(){this.map={};this.j=!1};
m.entries=function(){var a=[],b=Zc(this);b.sort();for(var c=0;c<b.length;c++){var d=this.map[b[c]];a.push([d.key,$c(this,d)])}return new ad(a)};
m.keys=function(){var a=[],b=Zc(this);b.sort();for(var c=0;c<b.length;c++)a.push(this.map[b[c]].key);return new ad(a)};
m.values=function(){var a=[],b=Zc(this);b.sort();for(var c=0;c<b.length;c++)a.push($c(this,this.map[b[c]]));return new ad(a)};
m.forEach=function(a,b){var c=Zc(this);c.sort();for(var d=0;d<c.length;d++){var e=this.map[c[d]];a.call(b,$c(this,e),e.key,this)}};
m.set=function(a,b){var c=new Yc(a);this.i?(c.h=b,c.value=b.T()):c.value=b;this.map[a.toString()]=c;this.j=!1;return this};
function $c(a,b){return a.i?(b.h||(b.h=new a.i(b.value)),b.h):b.value}
m.get=function(a){if(a=this.map[a.toString()])return $c(this,a)};
m.has=function(a){return a.toString()in this.map};
function Zc(a){a=a.map;var b=[],c;for(c in a)Object.prototype.hasOwnProperty.call(a,c)&&b.push(c);return b}
Xc.prototype[Symbol.iterator]=function(){return this.entries()};
function Yc(a,b){this.key=a;this.value=b;this.h=void 0}
function ad(a){this.i=0;this.h=a}
ad.prototype.next=function(){return this.i<this.h.length?{done:!1,value:this.h[this.i++]}:{done:!0,value:void 0}};
ad.prototype[Symbol.iterator]=function(){return this};var bd;function cd(a,b,c){var d=bd;bd=null;a||(a=d);d=this.constructor.Wm;a||(a=d?[d]:[]);this.l=(d?0:-1)-(this.constructor.Vm||0);this.h=null;this.i=a;a:{d=this.i.length;a=d-1;if(d&&(d=this.i[a],Sc(d))){this.u=a-this.l;this.j=d;break a}void 0!==b&&-1<b?(this.u=Math.max(b,a+1-this.l),this.j=null):this.u=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)a=c[b],a<this.u?(a+=this.l,(d=this.i[a])?Array.isArray(d)&&Pc(d):this.i[a]=dd):(ed(this),(d=this.j[a])?Array.isArray(d)&&Pc(d):this.j[a]=dd)}
var dd=Object.freeze(Pc([]));function ed(a){var b=a.u+a.l;a.i[b]||(a.j=a.i[b]={})}
function fd(a,b,c){return-1===b?null:(void 0===c?0:c)||b>=a.u?a.j?a.j[b]:void 0:a.i[b+a.l]}
function gd(a,b,c){a.h||(a.h={});if(b in a.h)return a.h[b];var d=fd(a,b);d||(d=Pc([]),hd(a,b,d));c=new Xc(d,c);return a.h[b]=c}
function hd(a,b,c,d){(void 0===d?0:d)||b>=a.u?(ed(a),a.j[b]=c):a.i[b+a.l]=c}
function id(a,b,c,d){if(-1===c)return null;a.h||(a.h={});var e=a.h[c];if(e)return e;d=fd(a,c,void 0===d?!1:d);if(null==d)return e;b=new b(d);return a.h[c]=b}
function jd(a,b,c,d){a.h||(a.h={});var e=a.h[c];if(!e){e=void 0===d?!1:d;e=void 0===e?!0:e;var f=void 0===f?!1:f;d=fd(a,c,f);null==d&&(d=dd);d===dd?(d=Pc([]),hd(a,c,d,f)):e&&Qc(d)&&(d=d.slice(),hd(a,c,d,f));f=d;e=[];d=Qc(f);for(var g=0;g<f.length;g++)e[g]=new b(f[g]),d&&Rc(e[g].i);d&&(Rc(e),Object.freeze(e));a.h[c]=e}return e}
cd.prototype.toJSON=function(){var a=this.T();return Vc(a,Tc)};
cd.prototype.T=function(){if(this.h)for(var a in this.h){var b=this.h[a];if(Array.isArray(b))for(var c=0;c<b.length;c++)b[c]&&b[c].T();else b&&b.T()}return this.i};
cd.prototype.toString=function(){return this.T().toString()};
cd.prototype.clone=function(){var a=this.constructor,b=Vc(this.T(),Wc);bd=b;a=new a(b);bd=null;kd(a,this);return a};
function kd(a,b){b.m&&(a.m=b.m.slice());var c=b.h;if(c){b=b.j;var d={},e;for(e in c){var f=c[e];if(f){var g=!(!b||!b[e]),h=+e;if(Array.isArray(f)){if(f.length)for(g=jd(a,f[0].constructor,h,g),h=0;h<Math.min(g.length,f.length);h++)kd(g[h],f[h])}else f instanceof Xc?f.i&&(d.Ha=gd(a,h,f.i),f.forEach(function(k){return function(l,n){return kd(k.Ha.get(n),l)}}(d))):(g=id(a,f.constructor,h,g))&&kd(g,f)}d={Ha:d.Ha}}}}
;var ld=window;wb("csi.gstatic.com");wb("googleads.g.doubleclick.net");wb("pagead2.googlesyndication.com");wb("partner.googleadservices.com");wb("pubads.g.doubleclick.net");wb("securepubads.g.doubleclick.net");wb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var md={};function nd(){}
function od(a){this.h=a}
v(od,nd);od.prototype.toString=function(){return this.h};
var pd=new od("about:invalid#zTSz",md);function qd(a){this.isValid=a}
function rd(a){return new qd(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var sd=[rd("data"),rd("http"),rd("https"),rd("mailto"),rd("ftp"),new qd(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function td(a){if(a instanceof nd)if(a instanceof od)a=a.h;else throw Error("");else a=Ob(a);return a}
;function ud(a,b){a.src=Bb(b);var c;b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document;var d=null===(c=b.querySelector)||void 0===c?void 0:c.call(b,"script[nonce]");(c=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function vd(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
m=vd.prototype;m.clone=function(){return new vd(this.x,this.y)};
m.equals=function(a){return a instanceof vd&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
m.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
m.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
m.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
m.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function wd(a,b){this.width=a;this.height=b}
m=wd.prototype;m.clone=function(){return new wd(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function xd(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function yd(a,b){hb(b,function(c,d){c&&"object"==typeof c&&c.ca&&(c=c.ba());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:zd.hasOwnProperty(d)?a.setAttribute(zd[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var zd={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function Ad(a,b,c){var d=arguments,e=document,f=d[1],g=Bd(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):yd(g,f));2<d.length&&Cd(e,g,d);return g}
function Cd(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!La(f)||Na(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(Na(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}E(g?fb(f):f,d)}}}
function Bd(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Dd(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Ed(a){var b=Fd;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Gd(){var a=[];Ed(function(b){a.push(b)});
return a}
var Fd={nc:"allow-forms",oc:"allow-modals",pc:"allow-orientation-lock",qc:"allow-pointer-lock",sc:"allow-popups",tc:"allow-popups-to-escape-sandbox",uc:"allow-presentation",wc:"allow-same-origin",xc:"allow-scripts",yc:"allow-top-navigation",zc:"allow-top-navigation-by-user-activation"},Hd=Za(function(){return Gd()});
function Id(){var a=Jd(),b={};E(Hd(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Jd(){var a=void 0===a?document:a;var b="IFRAME";"application/xhtml+xml"===(null==a?void 0:a.contentType)&&(b=b.toLowerCase());return a.createElement(b)}
;function Kd(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Ld=(new Date).getTime();function Md(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Nd(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var t=g,q=0;64>q;q+=4)t[q/4]=p[q]<<24|p[q+1]<<16|p[q+2]<<8|p[q+3];for(q=16;80>q;q++)p=t[q-3]^t[q-8]^t[q-14]^t[q-16],t[q]=(p<<1|p>>>31)&4294967295;p=e[0];var z=e[1],A=e[2],H=e[3],P=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var Q=H^z&(A^H);var S=1518500249}else Q=z^A^H,S=1859775393;else 60>q?(Q=z&A|H&(z|A),S=2400959708):(Q=z^A^H,S=3395469782);Q=((p<<5|p>>>27)&4294967295)+Q+P+S+t[q]&4294967295;P=H;H=A;A=(z<<30|z>>>2)&4294967295;z=p;p=Q}e[0]=e[0]+p&4294967295;e[1]=e[1]+z&4294967295;e[2]=
e[2]+A&4294967295;e[3]=e[3]+H&4294967295;e[4]=e[4]+P&4294967295}
function c(p,t){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var q=[],z=0,A=p.length;z<A;++z)q.push(p.charCodeAt(z));p=q}t||(t=p.length);q=0;if(0==l)for(;q+64<t;)b(p.slice(q,q+64)),q+=64,n+=64;for(;q<t;)if(f[l++]=p[q++],n++,64==l)for(l=0,b(f);q+64<t;)b(p.slice(q,q+64)),q+=64,n+=64}
function d(){var p=[],t=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=t&255,t>>>=8;b(f);for(q=t=0;5>q;q++)for(var z=24;0<=z;z-=8)p[t++]=e[q]>>z&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,yb:function(){for(var p=d(),t="",q=0;q<p.length;q++)t+="0123456789ABCDEF".charAt(Math.floor(p[q]/16))+"0123456789ABCDEF".charAt(p[q]%16);return t}}}
;function Od(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,Pd(Md(d),a,c||null)].join(" "):null}
function Pd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],E(d,function(h){e.push(h)}),Qd(e.join(" "));
var f=[],g=[];E(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];E(d,function(h){e.push(h)});
a=Qd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Qd(a){var b=Nd();b.update(a);return b.yb().toLowerCase()}
;var Rd={};function Sd(a){this.h=a||{cookie:""}}
m=Sd.prototype;m.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Sa:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.bn;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Sa}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Db(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Sa:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=Db(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var Td=new Sd("undefined"==typeof document?null:document);function Ud(a){return!!Rd.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Vd(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Ud(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new Sd(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");Ud(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Wd(a,b,c,d){(a=y[a])||(a=(new Sd(document)).get(b));return a?Od(a,c,d):null}
function Xd(a){var b=void 0===b?!1:b;var c=Md(String(y.location.href)),d=[];if(Vd(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new Sd(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?Od(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Ud(b)&&((b=Wd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Wd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Yd(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function Zd(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];La(d)?Zd.apply(null,d):Yd(d)}}
;function I(){this.h=this.h;this.u=this.u}
I.prototype.h=!1;I.prototype.dispose=function(){this.h||(this.h=!0,this.G())};
function $d(a,b){a.h?b():(a.u||(a.u=[]),a.u.push(b))}
I.prototype.G=function(){if(this.u)for(;this.u.length;)this.u.shift()()};function ae(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
ae.prototype.stopPropagation=function(){this.j=!0};
ae.prototype.preventDefault=function(){this.defaultPrevented=!0};function be(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ce(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,de[c])c=de[c];else{c=String(c);if(!de[c]){var f=/function\s+([^\(]+)/m.exec(c);de[c]=f?f[1]:"[Anonymous]"}c=de[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function ce(a,b){b||(b={});b[ee(a)]=!0;var c=a.stack||"";(a=a.wb)&&!b[ee(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=ce(a,b));return c}
function ee(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var de={};var fe=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",Ia,b),y.removeEventListener("test",Ia,b)}catch(c){}return a}();function ge(a,b){ae.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
D(ge,ae);var he={2:"touch",3:"pen",4:"mouse"};
ge.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(sc){a:{try{oc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:he[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&ge.S.preventDefault.call(this)};
ge.prototype.stopPropagation=function(){ge.S.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
ge.prototype.preventDefault=function(){ge.S.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var ie="closure_listenable_"+(1E6*Math.random()|0);var je=0;function ke(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Ca=e;this.key=++je;this.sa=this.xa=!1}
function le(a){a.sa=!0;a.listener=null;a.proxy=null;a.src=null;a.Ca=null}
;function me(a){this.src=a;this.listeners={};this.h=0}
me.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=ne(a,b,d,e);-1<g?(b=a[g],c||(b.xa=!1)):(b=new ke(b,this.src,f,!!d,e),b.xa=c,a.push(b));return b};
me.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=ne(e,b,c,d);return-1<b?(le(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function oe(a,b){var c=b.type;c in a.listeners&&eb(a.listeners[c],b)&&(le(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function ne(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.sa&&f.listener==b&&f.capture==!!c&&f.Ca==d)return e}return-1}
;var pe="closure_lm_"+(1E6*Math.random()|0),qe={},re=0;function se(a,b,c,d,e){if(d&&d.once)te(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)se(a,b[f],c,d,e);else c=ue(c),a&&a[ie]?a.U(b,c,Na(d)?!!d.capture:!!d,e):ve(a,b,c,!1,d,e)}
function ve(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Na(e)?!!e.capture:!!e,h=we(a);h||(a[pe]=h=new me(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=xe();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)fe||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(ye(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");re++}}
function xe(){function a(c){return b.call(a.src,a.listener,c)}
var b=ze;return a}
function te(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)te(a,b[f],c,d,e);else c=ue(c),a&&a[ie]?a.i.add(String(b),c,!0,Na(d)?!!d.capture:!!d,e):ve(a,b,c,!0,d,e)}
function Ae(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ae(a,b[f],c,d,e);else(d=Na(d)?!!d.capture:!!d,c=ue(c),a&&a[ie])?a.i.remove(String(b),c,d,e):a&&(a=we(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=ne(b,c,d,e)),(c=-1<a?b[a]:null)&&Be(c))}
function Be(a){if("number"!==typeof a&&a&&!a.sa){var b=a.src;if(b&&b[ie])oe(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(ye(c),d):b.addListener&&b.removeListener&&b.removeListener(d);re--;(c=we(b))?(oe(c,a),0==c.h&&(c.src=null,b[pe]=null)):le(a)}}}
function ye(a){return a in qe?qe[a]:qe[a]="on"+a}
function ze(a,b){if(a.sa)a=!0;else{b=new ge(b,this);var c=a.listener,d=a.Ca||a.src;a.xa&&Be(a);a=c.call(d,b)}return a}
function we(a){a=a[pe];return a instanceof me?a:null}
var Ce="__closure_events_fn_"+(1E9*Math.random()>>>0);function ue(a){if("function"===typeof a)return a;a[Ce]||(a[Ce]=function(b){return a.handleEvent(b)});
return a[Ce]}
;function J(){I.call(this);this.i=new me(this);this.R=this;this.F=null}
D(J,I);J.prototype[ie]=!0;J.prototype.addEventListener=function(a,b,c,d){se(this,a,b,c,d)};
J.prototype.removeEventListener=function(a,b,c,d){Ae(this,a,b,c,d)};
function De(a,b){var c=a.F;if(c){var d=[];for(var e=1;c;c=c.F)d.push(c),++e}a=a.R;c=b.type||b;"string"===typeof b?b=new ae(b,a):b instanceof ae?b.target=b.target||a:(e=b,b=new ae(c,a),rb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Ee(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Ee(g,c,!0,b)&&e,b.j||(e=Ee(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Ee(g,c,!1,b)&&e}
J.prototype.G=function(){J.S.G.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,le(d[e]);delete a.listeners[c];a.h--}}this.F=null};
J.prototype.U=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Ee(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.sa&&g.capture==c){var h=g.listener,k=g.Ca||g.src;g.xa&&oe(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Fe(a){var b,c;J.call(this);var d=this;this.B=this.l=0;this.P=null!==a&&void 0!==a?a:{L:function(e,f){return setTimeout(e,f)},
aa:clearTimeout};this.j=null!==(c=null===(b=window.navigator)||void 0===b?void 0:b.onLine)&&void 0!==c?c:!0;this.m=function(){return x(function(e){return w(e,Ge(d),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.B||He(this)}
v(Fe,J);Fe.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.P.aa(this.B);delete Fe.h};
Fe.prototype.I=function(){return this.j};
function He(a){a.B=a.P.L(function(){var b;return x(function(c){if(1==c.h)return a.j?(null===(b=window.navigator)||void 0===b?0:b.onLine)?c.A(3):w(c,Ge(a),3):w(c,Ge(a),3);He(a);c.h=0})},3E4)}
function Ge(a,b){return a.o?a.o:a.o=new Promise(function(c){var d,e,f;return x(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,ra(g,2,3),d&&(a.l=a.P.L(function(){d.abort()},b||2E4)),w(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:ta(g);a.o=void 0;a.l&&(a.P.aa(a.l),a.l=0);f!==a.j&&(a.j=f,a.j?De(a,"networkstatus-online"):De(a,"networkstatus-offline"));c(f);ua(g);break;case 2:sa(g),f=!1,g.A(3)}})})}
;function Ie(){this.data_=[];this.h=-1}
Ie.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Ie.prototype.get=function(a){return!!this.data_[a]};
function Je(a){-1==a.h&&(a.h=cb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Ke(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Ke.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Le(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Me;
function Ne(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!G("Presto")&&(a=function(){var e=Bd(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ta(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!G("Trident")&&!G("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.cb;c.cb=null;e()}};
return function(e){d.next={cb:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function Oe(){this.i=this.h=null}
Oe.prototype.add=function(a,b){var c=Pe.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
Oe.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var Pe=new Ke(function(){return new Qe},function(a){return a.reset()});
function Qe(){this.next=this.scope=this.h=null}
Qe.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
Qe.prototype.reset=function(){this.next=this.scope=this.h=null};function Re(a,b){Se||Te();Ue||(Se(),Ue=!0);Ve.add(a,b)}
var Se;function Te(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);Se=function(){a.then(We)}}else Se=function(){var b=We;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!G("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(Me||(Me=Ne()),Me(b)):y.setImmediate(b)}}
var Ue=!1,Ve=new Oe;function We(){for(var a;a=Ve.remove();){try{a.h.call(a.scope)}catch(b){mc(b)}Le(Pe,a)}Ue=!1}
;function Xe(a,b){this.h=a[y.Symbol.iterator]();this.i=b;this.j=0}
Xe.prototype[Symbol.iterator]=function(){return this};
Xe.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function Ye(a,b){return new Xe(a,b)}
;function Ze(){this.blockSize=-1}
;function $e(){this.blockSize=-1;this.blockSize=64;this.h=[];this.u=[];this.m=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
D($e,Ze);$e.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function af(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
$e.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.u,f=this.i;d<b;){if(0==f)for(;d<=c;)af(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){af(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){af(this,e);f=0;break}}this.i=f;this.l+=b}};
$e.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.u[c]=b&255,b/=256;af(this,this.u);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function bf(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function cf(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function df(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:bf(a).match(/\S+/g)||[],b=0<=$a(a,b));return b}
function ef(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):df(a,"inverted-hdpi")&&cf(a,Array.prototype.filter.call(a.classList?a.classList:bf(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;var ff="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function gf(){}
gf.prototype.V=function(){throw ff;};
gf.prototype.next=function(){return hf};
var hf={done:!0,value:void 0};function jf(a){return{value:a,done:!1}}
function kf(a){if(a.done)throw ff;return a.value}
gf.prototype.O=function(){return this};function lf(a){if(a instanceof mf||a instanceof nf||a instanceof of)return a;if("function"==typeof a.V)return new mf(function(){return pf(a)});
if("function"==typeof a[Symbol.iterator])return new mf(function(){return a[Symbol.iterator]()});
if("function"==typeof a.O)return new mf(function(){return pf(a.O())});
throw Error("Not an iterator or iterable.");}
function pf(a){if(!(a instanceof gf))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.V();break}catch(d){if(d!==ff)throw d;b=!0}return{value:c,done:b}}}}
function mf(a){this.h=a}
mf.prototype.O=function(){return new nf(this.h())};
mf.prototype[Symbol.iterator]=function(){return new of(this.h())};
mf.prototype.i=function(){return new of(this.h())};
function nf(a){this.h=a}
v(nf,gf);nf.prototype.V=function(){var a=this.h.next();if(a.done)throw ff;return a.value};
nf.prototype.next=function(){return this.h.next()};
nf.prototype[Symbol.iterator]=function(){return new of(this.h)};
nf.prototype.i=function(){return new of(this.h)};
function of(a){mf.call(this,function(){return a});
this.j=a}
v(of,mf);of.prototype.next=function(){return this.j.next()};function qf(a,b){this.i={};this.h=[];this.ga=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof qf)for(c=rf(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function rf(a){sf(a);return a.h.concat()}
m=qf.prototype;m.has=function(a){return tf(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||uf;sf(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function uf(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.ga=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return tf(this.i,a)?(delete this.i[a],--this.size,this.ga++,this.h.length>2*this.size&&sf(this),!0):!1};
function sf(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];tf(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],tf(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return tf(this.i,a)?this.i[a]:b};
m.set=function(a,b){tf(this.i,a)||(this.size+=1,this.h.push(a),this.ga++);this.i[a]=b};
m.forEach=function(a,b){for(var c=rf(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new qf(this)};
m.keys=function(){return lf(this.O(!0)).i()};
m.values=function(){return lf(this.O(!1)).i()};
m.entries=function(){var a=this;return Ye(this.keys(),function(b){return[b,a.get(b)]})};
m.O=function(a){sf(this);var b=0,c=this.ga,d=this,e=new gf;e.next=function(){if(c!=d.ga)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return hf;var g=d.h[b++];return jf(a?g:d.i[g])};
var f=e.next;e.V=function(){return kf(f.call(e))};
return e};
function tf(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function vf(a){wf();return Cb(a)}
var wf=Ia;function xf(a){var b=[];yf(new zf,a,b);return b.join("")}
function zf(){}
function yf(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),yf(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Af(d,c),c.push(":"),yf(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Af(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Bf={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Cf=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Af(a,b){b.push('"',a.replace(Cf,function(c){var d=Bf[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Bf[c]=d);return d}),'"')}
;function Df(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function Ef(a){this.h=0;this.o=void 0;this.l=this.i=this.j=null;this.u=this.m=!1;if(a!=Ia)try{var b=this;a.call(void 0,function(c){Ff(b,2,c)},function(c){Ff(b,3,c)})}catch(c){Ff(this,3,c)}}
function Gf(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Gf.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var Hf=new Ke(function(){return new Gf},function(a){a.reset()});
function Jf(a,b,c){var d=Hf.get();d.i=a;d.onRejected=b;d.context=c;return d}
function Kf(a){return new Ef(function(b,c){c(a)})}
Ef.prototype.then=function(a,b,c){return Lf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ef.prototype.$goog_Thenable=!0;function Mf(a,b){return Lf(a,null,b,void 0)}
Ef.prototype.cancel=function(a){if(0==this.h){var b=new Nf(a);Re(function(){Of(this,b)},this)}};
function Of(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Of(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Pf(c),Qf(c,e,3,b)))}a.j=null}else Ff(a,3,b)}
function Rf(a,b){a.i||2!=a.h&&3!=a.h||Sf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Lf(a,b,c,d){var e=Jf(null,null,null);e.h=new Ef(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Nf?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Rf(a,e);return e.h}
Ef.prototype.F=function(a){this.h=0;Ff(this,2,a)};
Ef.prototype.H=function(a){this.h=0;Ff(this,3,a)};
function Ff(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.F,f=a.H;if(d instanceof Ef){Rf(d,Jf(e||Ia,f||null,a));var g=!0}else if(Df(d))d.then(e,f,a),g=!0;else{if(Na(d))try{var h=d.then;if("function"===typeof h){Tf(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.o=c,a.h=b,a.j=null,Sf(a),3!=b||c instanceof Nf||Uf(a,c))}}
function Tf(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Sf(a){a.m||(a.m=!0,Re(a.B,a))}
function Pf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Ef.prototype.B=function(){for(var a;a=Pf(this);)Qf(this,a,this.h,this.o);this.m=!1};
function Qf(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.u;a=a.j)a.u=!1;if(b.h)b.h.j=null,Vf(b,c,d);else try{b.j?b.i.call(b.context):Vf(b,c,d)}catch(e){Wf.call(null,e)}Le(Hf,b)}
function Vf(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Uf(a,b){a.u=!0;Re(function(){a.u&&Wf.call(null,b)})}
var Wf=mc;function Nf(a){Xa.call(this,a)}
D(Nf,Xa);Nf.prototype.name="cancel";function K(a){I.call(this);this.o=1;this.l=[];this.m=0;this.i=[];this.j={};this.B=!!a}
D(K,I);m=K.prototype;m.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.o;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.o=e+3;d.push(e);return e};
function Xf(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.oa(b)}}
m.oa=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=Ia):(c&&eb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
m.ha=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.B)for(e=0;e<c.length;e++){var g=c[e];Yf(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.oa(c)}}return 0!=e}return!1};
function Yf(a,b,c){Re(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.oa,this),delete this.j[a])}else this.i.length=0,this.j={}};
m.G=function(){K.S.G.call(this);this.clear();this.l.length=0};function Zf(a){this.h=a}
Zf.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,xf(b))};
Zf.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Zf.prototype.remove=function(a){this.h.remove(a)};function $f(a){this.h=a}
D($f,Zf);function ag(a){this.data=a}
function bg(a){return void 0===a||a instanceof ag?a:new ag(a)}
$f.prototype.set=function(a,b){$f.S.set.call(this,a,bg(b))};
$f.prototype.i=function(a){a=$f.S.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
$f.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function cg(a){this.h=a}
D(cg,$f);cg.prototype.set=function(a,b,c){if(b=bg(b)){if(c){if(c<Date.now()){cg.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}cg.S.set.call(this,a,b)};
cg.prototype.i=function(a){var b=cg.S.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())cg.prototype.remove.call(this,a);else return b}};function dg(){}
;function eg(){}
D(eg,dg);eg.prototype[Symbol.iterator]=function(){return lf(this.O(!0)).i()};
eg.prototype.clear=function(){var a=Array.from(this);a=u(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function fg(a){this.h=a}
D(fg,eg);m=fg.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.O=function(a){var b=0,c=this.h,d=new gf;d.next=function(){if(b>=c.length)return hf;var f=c.key(b++);if(a)return jf(f);f=c.getItem(f);if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return jf(f)};
var e=d.next;d.V=function(){return kf(e.call(d))};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function gg(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
D(gg,fg);function hg(a,b){this.i=a;this.h=null;var c;if(c=qc)c=!(9<=Number(Dc));if(c){ig||(ig=new qf);this.h=ig.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),ig.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
D(hg,eg);var jg={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},ig=null;function kg(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return jg[b]})}
m=hg.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(kg(a),b);lg(this)};
m.get=function(a){a=this.h.getAttribute(kg(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(kg(a));lg(this)};
m.O=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new gf;d.next=function(){if(b>=c.length)return hf;var f=c[b++];if(a)return jf(decodeURIComponent(f.nodeName.replace(/\./g,"%")).substr(1));f=f.nodeValue;if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return jf(f)};
var e=d.next;d.V=function(){return kf(e.call(d))};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);lg(this)};
function lg(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function mg(a,b){this.i=a;this.h=b+"::"}
D(mg,eg);mg.prototype.set=function(a,b){this.i.set(this.h+a,b)};
mg.prototype.get=function(a){return this.i.get(this.h+a)};
mg.prototype.remove=function(a){this.i.remove(this.h+a)};
mg.prototype.O=function(a){var b=this.i.O(!0),c=this,d=new gf;d.next=function(){try{var f=b.V()}catch(g){if(g===ff)return hf;throw g;}for(;f.substr(0,c.h.length)!=c.h;)try{f=b.V()}catch(g){if(g===ff)return hf;throw g;}return jf(a?f.substr(c.h.length):c.i.get(f))};
var e=d.next;d.V=function(){return kf(e.call(d))};
return d};function ng(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;function og(a){cd.call(this,a)}
v(og,cd);var pg,qg,rg,sg=y.window,tg=(null===(pg=null===sg||void 0===sg?void 0:sg.yt)||void 0===pg?void 0:pg.config_)||(null===(qg=null===sg||void 0===sg?void 0:sg.ytcfg)||void 0===qg?void 0:qg.data_)||{},ug=(null===(rg=null===sg||void 0===sg?void 0:sg.ytcfg)||void 0===rg?void 0:rg.obfuscatedData_)||[];function vg(){og.apply(this,arguments)}
v(vg,og);new vg(ug);B("yt.config_",tg,void 0);B("yt.configJspb_",ug,void 0);function L(){ng(tg,arguments)}
function F(a,b){return a in tg?tg[a]:b}
;var wg=[];function xg(a){wg.forEach(function(b){return b(a)})}
function yg(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){zg(b)}}:a}
function zg(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=F("ERRORS",[]),e.push([a,"ERROR",b,c,d]),L("ERRORS",e));xg(a)}
function Ag(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=F("ERRORS",[]),e.push([a,"WARNING",b,c,d]),L("ERRORS",e))}
;var Bg=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};B("yt.msgs_",Bg,void 0);function Cg(a){ng(Bg,arguments)}
;function M(a){a=Dg(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Eg(a,b){a=Dg(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Dg(a){var b=F("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:F("EXPERIMENT_FLAGS",{})[a]}
;var Fg={appSettingsCaptured:!0,visualElementAttached:!0,visualElementGestured:!0,visualElementHidden:!0,visualElementShown:!0,flowEvent:!0,visualElementStateChanged:!0,playbackAssociated:!0,youThere:!0,accountStateChangeSignedIn:!0,accountStateChangeSignedOut:!0},Gg={latencyActionBaselined:!0,latencyActionInfo:!0,latencyActionTicked:!0,bedrockRepetitiveActionTimed:!0,adsClientStateChange:!0,streamzIncremented:!0,mdxDialAdditionalDataUpdateEvent:!0,tvhtml5WatchKeyEvent:!0,tvhtml5VideoSeek:!0,tokenRefreshEvent:!0,
adNotify:!0,adNotifyFilled:!0,tvhtml5LaunchUrlComponentChanged:!0,bedrockResourceConsumptionSnapshot:!0,deviceStartupMetrics:!0,mdxSignIn:!0,tvhtml5KeyboardLogging:!0,tvhtml5StartupSoundEvent:!0,tvhtml5LiveChatStatus:!0,tvhtml5DeviceStorageStatus:!0,tvhtml5LocalStorage:!0,directSignInEvent:!0,finalPayload:!0,tvhtml5SearchCompleted:!0,tvhtml5KeyboardPerformance:!0,adNotifyFailure:!0,latencyActionSpan:!0,tvhtml5AccountDialogOpened:!0,tvhtml5ApiTest:!0};var Hg=0,Ig=tc?"webkit":sc?"moz":qc?"ms":pc?"o":"";B("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++Hg},void 0);var Jg={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Kg(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Jg||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function Lg(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
Kg.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Kg.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Kg.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var jb=y.ytEventsEventsListeners||{};B("ytEventsEventsListeners",jb,void 0);var Mg=y.ytEventsEventsCounter||{count:0};B("ytEventsEventsCounter",Mg,void 0);
function Ng(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return ib(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Na(e[4])&&Na(d)&&nb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Og=Za(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Pg(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Ng(a,b,c,d);if(e)return e;e=++Mg.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Kg(h);if(!Dd(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Kg(h);
h.currentTarget=a;return c.call(a,h)};
g=yg(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Og()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);jb[e]=[a,b,c,g,d];return e}
function Qg(a){a&&("string"==typeof a&&(a=[a]),E(a,function(b){if(b in jb){var c=jb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Og()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete jb[b]}}))}
;var Rg=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Sg(a,b){"function"===typeof a&&(a=yg(a));return window.setTimeout(a,b)}
function Tg(a){window.clearTimeout(a)}
;function Ug(a){this.F=a;this.i=null;this.m=0;this.B=null;this.o=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.N=Pg(window,"mousemove",Ta(this.R,this));a=Ta(this.H,this);"function"===typeof a&&(a=yg(a));this.Y=window.setInterval(a,25)}
D(Ug,I);Ug.prototype.R=function(a){void 0===a.h&&Lg(a);var b=a.h;void 0===a.i&&Lg(a);this.i=new vd(b,a.i)};
Ug.prototype.H=function(){if(this.i){var a=Rg();if(0!=this.m){var b=this.B,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.o)/this.o)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.F();this.o=d}this.m=a;this.B=this.i;this.l=(this.l+1)%4}};
Ug.prototype.G=function(){window.clearInterval(this.Y);Qg(this.N)};function Vg(){}
function Wg(a,b){return Xg(a,0,b)}
Vg.prototype.L=function(a,b){return Xg(a,1,b)};function Yg(){Vg.apply(this,arguments)}
v(Yg,Vg);function Zg(){Yg.h||(Yg.h=new Yg);return Yg.h}
function Xg(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Sg(a,c||0)}
Yg.prototype.aa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):Tg(a)}};
Yg.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
Yg.prototype.pause=function(){var a=C("yt.scheduler.instance.pause");a&&a()};var $g=Zg();var ah={};
function bh(a){var b=void 0===a?{}:a;a=void 0===b.Nb?!1:b.Nb;b=void 0===b.Ab?!0:b.Ab;if(null==C("_lact",window)){var c=parseInt(F("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;B("_lact",c,window);B("_fact",c,window);-1==c&&ch();Pg(document,"keydown",ch);Pg(document,"keyup",ch);Pg(document,"mousedown",ch);Pg(document,"mouseup",ch);a?Pg(window,"touchmove",function(){dh("touchmove",200)},{passive:!0}):(Pg(window,"resize",function(){dh("resize",200)}),b&&Pg(window,"scroll",function(){dh("scroll",200)}));
new Ug(function(){dh("mouse",100)});
Pg(document,"touchstart",ch,{passive:!0});Pg(document,"touchend",ch,{passive:!0})}}
function dh(a,b){ah[a]||(ah[a]=!0,$g.L(function(){ch();ah[a]=!1},b))}
function ch(){null==C("_lact",window)&&bh();var a=Date.now();B("_lact",a,window);-1==C("_fact",window)&&B("_fact",a,window);(a=C("ytglobal.ytUtilActivityCallback_"))&&a()}
function eh(){var a=C("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;function fh(){var a=gh;C("yt.ads.biscotti.getId_")||B("yt.ads.biscotti.getId_",a,void 0)}
function hh(a){B("yt.ads.biscotti.lastId_",a,void 0)}
;var ih=/^[\w.]*$/,jh={q:!0,search_query:!0};function kh(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=lh(f[0]||""),h=lh(f[1]||"");g in c?Array.isArray(c[g])?gb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(kh);k.args=[{key:l,value:f[1],query:a,method:mh==n?"unchanged":n}];jh.hasOwnProperty(l)||Ag(k)}}return c}
var mh=String(kh);function nh(a){var b=[];hb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];E(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function oh(a){"?"==a.charAt(0)&&(a=a.substr(1));return kh(a,"&")}
function ph(){var a=window.location.href;return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),oh(1<a.length?a[1]:a[0])):{}}
function qh(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=oh(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return kc(a,e)+d}
function rh(a){if(!b)var b=window.location.href;var c=a.match(fc)[1]||null,d=hc(a);c&&d?(a=a.match(fc),b=b.match(fc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?hc(b)==d&&(Number(b.match(fc)[4]||null)||null)==(Number(a.match(fc)[4]||null)||null):!0;return a}
function lh(a){return a&&a.match(ih)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function sh(a){var b=th;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Ld;e.flash="0";a:{try{var f=b.h.top.location.href}catch(Ma){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?ld:g;try{var h=g.history.length}catch(Ma){h=0}e.u_his=h;var k;e.u_h=null==(k=ld.screen)?void 0:k.height;var l;e.u_w=null==(l=ld.screen)?void 0:l.width;var n;e.u_ah=null==(n=ld.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=ld.screen)?void 0:p.availWidth;var t;e.u_cd=null==(t=ld.screen)?void 0:t.colorDepth}catch(Ma){}h=b.h;try{var q=h.screenX;var z=h.screenY}catch(Ma){}try{var A=h.outerWidth;var H=h.outerHeight}catch(Ma){}try{var P=h.innerWidth;var Q=h.innerHeight}catch(Ma){}try{var S=h.screenLeft;var Ec=h.screenTop}catch(Ma){}try{P=h.innerWidth,Q=h.innerHeight}catch(Ma){}try{var If=h.screen.availWidth;var on=h.screen.availTop}catch(Ma){}q=[S,Ec,q,z,If,on,A,H,P,Q];z=b.h.top;try{var Jb=(z||window).document,za=
"CSS1Compat"==Jb.compatMode?Jb.documentElement:Jb.body;var Ba=(new wd(za.clientWidth,za.clientHeight)).round()}catch(Ma){Ba=new wd(-12245933,-12245933)}Jb=Ba;Ba={};za=new Ie;y.SVGElement&&y.document.createElementNS&&za.set(0);z=Id();z["allow-top-navigation-by-user-activation"]&&za.set(1);z["allow-popups-to-escape-sandbox"]&&za.set(2);y.crypto&&y.crypto.subtle&&za.set(3);y.TextDecoder&&y.TextEncoder&&za.set(4);za=Je(za);Ba.bc=za;Ba.bih=Jb.height;Ba.biw=Jb.width;Ba.brdim=q.join();b=b.i;b=(Ba.vis={visible:1,
hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,Ba.wgl=!!ld.WebGLRenderingContext,Ba);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var th=new function(){var a=window.document;this.h=window;this.i=a};
B("yt.ads_.signals_.getAdSignalsString",function(a){return nh(sh(a))},void 0);Date.now();var uh="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function vh(){if(!uh)return null;var a=uh();return"open"in a?a:null}
function wh(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var xh={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},yh="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(fa("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),zh=!1;
function Ah(a,b){b=void 0===b?{}:b;var c=rh(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in xh){var f=F(xh[e]);!f||!c&&hc(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!hc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!hc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!hc(a))b["X-YouTube-Ad-Signals"]=nh(sh(void 0));return b}
function Bh(a){var b=window.location.search,c=hc(a);M("debug_handle_relative_url_for_query_forward_killswitch")||c||!rh(a)||(c=document.location.hostname);var d=gc(a.match(fc)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=oh(b),f={};E(yh,function(g){e[g]&&(f[g]=e[g])});
return qh(a,f||{},!1)}
function Ch(a,b){var c=b.format||"JSON";a=Dh(a,b);var d=Eh(a,b),e=!1,f=Fh(a,function(k){if(!e){e=!0;h&&Tg(h);var l=wh(k),n=null,p=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||p||t)n=Gh(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=!!n}n=n||{};p=b.context||y;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=Sg(function(){e||(e=!0,f.abort(),Tg(h),g.call(b.context||y,f))},b.timeout)}return f}
function Dh(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=F("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=qh(a,b||{},!0);return a}
function Eh(a,b){var c=F("XSRF_FIELD_NAME",void 0),d=F("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=F("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||hc(a)&&!b.withCredentials&&hc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=oh(e),rb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):jc(e));f=e||f&&!kb(f);!zh&&f&&
"POST"!=b.method&&(zh=!0,zg(Error("AJAX request with postData should use POST")));return e}
function Gh(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Ag(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Hh(a):null)e={},E(a.getElementsByTagName("*"),function(g){e[g.tagName]=Ih(g)})}d&&Jh(e);
return e}
function Jh(a){if(Na(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;wb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Zb(a[b],null);a[c]=d}else Jh(a[b])}}
function Hh(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Ih(a){var b="";E(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Fh(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&yg(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=vh();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=Bh(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Ah(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Kh=Fc||Gc;function Lh(a){var b=Tb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Mh={},Nh=0;
function Oh(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Lh("cobalt")){if(a){a instanceof Mb||(a="object"==typeof a&&a.ca?a.ba():String(a),Rb.test(a)?a=new Mb(a,Nb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Qb))&&Pb.test(b[1])?new Mb(a,Nb):null));b=Ob(a||Sb);if("about:invalid#zClosurez"===b||b.startsWith("data"))a="";else{if(b instanceof Yb)a=b;else{var f="object"==typeof b;a=null;f&&b.Pa&&(a=b.La());b=f&&b.ca?b.ba():String(b);Lb.test(b)&&(-1!=b.indexOf("&")&&(b=b.replace(Eb,"&amp;")),-1!=
b.indexOf("<")&&(b=b.replace(Fb,"&lt;")),-1!=b.indexOf(">")&&(b=b.replace(Gb,"&gt;")),-1!=b.indexOf('"')&&(b=b.replace(Hb,"&quot;")),-1!=b.indexOf("'")&&(b=b.replace(Ib,"&#39;")),-1!=b.indexOf("\x00")&&(b=b.replace(Kb,"&#0;")));a=Zb(b,a)}a instanceof Yb&&a.constructor===Yb?a=a.h:(Ka(a),a="type_error:SafeHtml");a=encodeURIComponent(String(xf(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=Ad("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||
a.document).body.appendChild(a))}}else if(e)Fh(a,b,"POST",e,d);else if(F("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)Fh(a,b,"GET","",d);else{b:{try{var g=new Ya({url:a});if(g.j&&g.i||g.l){var h=gc(a.match(fc)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(lc);d:{for(c=0;0<=(c=a.indexOf("ri",c))&&c<l;){var n=a.charCodeAt(c-1);if(38==n||63==n){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var t=c;break d}}c+=3}t=-1}if(0>t)var q=null;else{var z=a.indexOf("&",t);if(0>z||z>l)z=l;t+=3;
q=decodeURIComponent(a.substr(t,z-t).replace(/\+/g," "))}k="1"!==q}f=!k;break b}}catch(A){}f=!1}f?Ph(a)?(b&&b(),f=!0):f=!1:f=!1;f||Qh(a,b)}}
function Rh(a){var b=void 0===b?"":b;Ph(a,b)||Oh(a,void 0,void 0,void 0,b)}
function Ph(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Qh(a,b){var c=new Image,d=""+Nh++;Mh[d]=c;c.onload=c.onerror=function(){b&&Mh[d]&&b();delete Mh[d]};
c.src=a}
;var Sh=y.ytPubsubPubsubInstance||new K,Th=y.ytPubsubPubsubSubscribedKeys||{},Uh=y.ytPubsubPubsubTopicToKeys||{},Vh=y.ytPubsubPubsubIsSynchronous||{};function Wh(a,b){var c=Xh();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Th[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Vh[a]?f():Sg(f,0)}catch(g){zg(g)}},void 0);
Th[d]=!0;Uh[a]||(Uh[a]=[]);Uh[a].push(d);return d}return 0}
function Yh(a){var b=Xh();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),E(a,function(c){b.unsubscribeByKey(c);delete Th[c]}))}
function Zh(a,b){var c=Xh();c&&c.publish.apply(c,arguments)}
function $h(a){var b=Xh();if(b)if(b.clear(a),a)ai(a);else for(var c in Uh)ai(c)}
function Xh(){return y.ytPubsubPubsubInstance}
function ai(a){Uh[a]&&(a=Uh[a],E(a,function(b){Th[b]&&delete Th[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.oa;K.prototype.publish=K.prototype.ha;K.prototype.clear=K.prototype.clear;B("ytPubsubPubsubInstance",Sh,void 0);B("ytPubsubPubsubTopicToKeys",Uh,void 0);B("ytPubsubPubsubIsSynchronous",Vh,void 0);B("ytPubsubPubsubSubscribedKeys",Th,void 0);var bi=window,N=bi.ytcsi&&bi.ytcsi.now?bi.ytcsi.now:bi.performance&&bi.performance.timing&&bi.performance.now&&bi.performance.timing.navigationStart?function(){return bi.performance.timing.navigationStart+bi.performance.now()}:function(){return(new Date).getTime()};var ci=Eg("initial_gel_batch_timeout",2E3),di=Math.pow(2,16)-1,ei=void 0,fi=0,gi=0,hi=0,ii=!0,ji=y.ytLoggingTransportGELQueue_||new Map;B("ytLoggingTransportGELQueue_",ji,void 0);var ki=y.ytLoggingTransportTokensToCttTargetIds_||{};B("ytLoggingTransportTokensToCttTargetIds_",ki,void 0);
function li(a,b){if("log_event"===a.endpoint){var c="";a.Aa?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(ki[a.cttAuthInfo.token]=mi(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=ji.get(c)||[];ji.set(c,d);d.push(a.payload);b&&(ei=new b);a=Eg("tvhtml5_logging_max_batch")||Eg("web_logging_max_batch")||100;b=N();d.length>=a?ni({writeThenSend:!0},M("flush_only_full_queue")?c:void 0):10<=b-hi&&(oi(),hi=b)}}
function pi(a,b){if("log_event"===a.endpoint){var c="";a.Aa?c="visitorOnlyApprovedKey":a.cttAuthInfo&&(ki[a.cttAuthInfo.token]=mi(a.cttAuthInfo),c=a.cttAuthInfo.token);var d=new Map;d.set(c,[a.payload]);b&&(ei=new b);return new Ef(function(e){ei&&ei.isReady()?qi(d,e,{bypassNetworkless:!0},!0):e()})}}
function ni(a,b){a=void 0===a?{}:a;new Ef(function(c){Tg(fi);Tg(gi);gi=0;if(ei&&ei.isReady())if(void 0!==b){var d=new Map,e=ji.get(b)||[];d.set(b,e);qi(d,c,a);ji.delete(b)}else qi(ji,c,a),ji.clear();else oi(),c()})}
function oi(){M("web_gel_timeout_cap")&&!gi&&(gi=Sg(function(){ni({writeThenSend:!0})},6E4));
Tg(fi);var a=F("LOGGING_BATCH_TIMEOUT",Eg("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&ii&&(a=ci);fi=Sg(function(){ni({writeThenSend:!0})},a)}
function qi(a,b,c,d){var e=ei;c=void 0===c?{}:c;var f=Math.round(N()),g=a.size;a=u(a);for(var h=a.next();!h.done;h=a.next()){var k=u(h.value);h=k.next().value;var l=k=k.next().value;k=pb({context:ri(e.config_||si())});k.events=l;(l=ki[h])&&ti(k,h,l);delete ki[h];h="visitorOnlyApprovedKey"===h;ui(k,f,h);M("always_send_and_write")&&(c.writeThenSend=!1);M("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Rh("/generate_204");vi(e,"log_event",k,{retry:!0,onSuccess:function(){g--;
g||b()},
onError:function(){g--;g||b()},
lb:c,Aa:h,Rm:!!d});ii=!1}}
function ui(a,b,c){a.requestTimeMs=String(b);M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=F("EVENT_ID",void 0))&&((c=F("BATCH_CLIENT_COUNTER",void 0)||0)||(c=Math.floor(Math.random()*di/2)),c++,c>di&&(c=1),L("BATCH_CLIENT_COUNTER",c),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function ti(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function mi(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var wi=y.ytLoggingGelSequenceIdObj_||{};B("ytLoggingGelSequenceIdObj_",wi,void 0);
function xi(a,b,c,d){d=void 0===d?{}:d;if(M("lr_drop_other_and_business_payloads")){if(Gg[a]||Fg[a])return}else if(M("lr_drop_other_payloads")&&Gg[a])return;var e={},f=Math.round(d.timestamp||N());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=eh();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.fa&&(a=e.context,b=d.fa,wi[b]=b in wi?wi[b]+1:0,a.sequence={index:wi[b],groupKey:b},d.Bb&&delete wi[d.fa]);(d.cn?pi:li)({endpoint:"log_event",payload:e,
cttAuthInfo:d.cttAuthInfo,Aa:d.Aa},c)}
;function yi(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function zi(a,b,c,d,e){Td.set(""+a,b,{Sa:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
;var Ai=C("ytglobal.prefsUserPrefsPrefs_")||{};B("ytglobal.prefsUserPrefsPrefs_",Ai,void 0);function Bi(){this.h=F("ALT_PREF_COOKIE_NAME","PREF");this.i=F("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=Td.get(""+this.h,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Ai[d]=c.toString())}}}
Bi.prototype.get=function(a,b){Ci(a);Di(a);a=void 0!==Ai[a]?Ai[a].toString():null;return null!=a?a:b?b:""};
Bi.prototype.set=function(a,b){Ci(a);Di(a);if(null==b)throw Error("ExpectedNotNull");Ai[a]=b.toString()};
Bi.prototype.remove=function(a){Ci(a);Di(a);delete Ai[a]};
Bi.prototype.clear=function(){for(var a in Ai)delete Ai[a]};
function Di(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Ci(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Ei(a){a=void 0!==Ai[a]?Ai[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ja(Bi);var Fi={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Gi={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Hi(){var a=y.navigator;return a?a.connection:void 0}
;function Ii(){return"INNERTUBE_API_KEY"in tg&&"INNERTUBE_API_VERSION"in tg}
function si(){return{innertubeApiKey:F("INNERTUBE_API_KEY",void 0),innertubeApiVersion:F("INNERTUBE_API_VERSION",void 0),Db:F("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Qa:F("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Um:F("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Fb:F("INNERTUBE_CONTEXT_HL",void 0),Eb:F("INNERTUBE_CONTEXT_GL",void 0),Gb:F("INNERTUBE_HOST_OVERRIDE",void 0)||"",Ib:!!F("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Hb:!!F("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:F("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function ri(a){var b={client:{hl:a.Fb,gl:a.Eb,clientName:a.Qa,clientVersion:a.innertubeContextClientVersion,configInfo:a.Db}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=F("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=F("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=F("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===
d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});f=a.Qa;if(("WEB"===f||"MWEB"===f||1===f||2===f)&&b){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=yi()}g=a.Qa;if(("WEB_REMIX"===g||76===g)&&!M("music_web_display_mode_killswitch")&&b){var h;b.client.kb=null!=(h=b.client.kb)?h:{};b.client.kb.webDisplayMode=yi()}var k;if(M("web_log_memory_total_kbytes")&&(null==(k=y.navigator)?0:k.deviceMemory)){var l;
h=null==(l=y.navigator)?void 0:l.deviceMemory;b&&(b.client.memoryTotalKbytes=""+1E6*h)}a.appInstallData&&b&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);a:{if(l=Hi()){a=Fi[l.type||"unknown"]||"CONN_UNKNOWN";l=Fi[l.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==l&&(a=l);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==l){a=l;break a}}a=void 0}a&&b&&(b.client.connectionType=a);M("web_log_effective_connection_type")&&
(a=Hi(),a=null!==a&&void 0!==a&&a.effectiveType?Gi.hasOwnProperty(a.effectiveType)?Gi[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&b&&(b.client.effectiveConnectionType=a));F("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(b.user={onBehalfOfUser:F("DELEGATED_SESSION_ID")});a=Object;l=a.assign;h=b.client;k={};g=u(Object.entries(oh(F("DEVICE",""))));for(f=g.next();!f.done;f=g.next())e=u(f.value),f=e.next().value,e=e.next().value,"cbrand"===f?k.deviceMake=e:"cmodel"===f?k.deviceModel=
e:"cbr"===f?k.browserName=e:"cbrver"===f?k.browserVersion=e:"cos"===f?k.osName=e:"cosver"===f?k.osVersion=e:"cplatform"===f&&(k.platform=e);b.client=l.call(a,h,k);return b}
function Ji(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||F("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Pm||F("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().Om:b=Xd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=F("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=F("DELEGATED_SESSION_ID")));return d}
;function Ki(a){a=Object.assign({},a);delete a.Authorization;var b=Xd();if(b){var c=new $e;c.update(F("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=Kc(c.digest(),3)}return a}
;function Li(a){var b=new gg;(b=b.isAvailable()?a?new mg(b,a):b:null)||(a=new hg(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new cg(a):null;this.i=document.domain||window.location.hostname}
Li.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(xf(b))}catch(f){return}else e=escape(b);zi(a,e,c,this.i)};
Li.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=Td.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Li.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;Td.remove(""+a,"/",void 0===b?"youtube.com":b)};var Mi;function Ni(){Mi||(Mi=new Li("yt.innertube"));return Mi}
function Oi(a,b,c,d){if(d)return null;d=Ni().get("nextId",!0)||1;var e=Ni().get("requests",!0)||{};e[d]={method:a,request:b,authState:Ki(c),requestTime:Math.round(N())};Ni().set("nextId",d+1,86400,!0);Ni().set("requests",e,86400,!0);return d}
function Pi(a){var b=Ni().get("requests",!0)||{};delete b[a];Ni().set("requests",b,86400,!0)}
function Qi(a){var b=Ni().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(N())-d.requestTime)){var e=d.authState,f=Ki(Ji(!1));nb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(N())),vi(a,d.method,e,{}));delete b[c]}}Ni().set("requests",b,86400,!0)}}
;var Ri=function(){var a;return function(){a||(a=new Li("ytidb"));return a}}();
function Si(){var a;return null===(a=Ri())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Ti=[],Ui=!1;function Vi(a){Ui||(Ti.push({type:"ERROR",payload:a}),10<Ti.length&&Ti.shift())}
function Wi(a,b){Ui||(Ti.push({type:"EVENT",eventType:a,payload:b}),10<Ti.length&&Ti.shift())}
;function Xi(a){var b=Da.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(fa(b))}
v(Xi,Error);function Yi(){try{return Zi(),!0}catch(a){return!1}}
function Zi(){if(void 0!==F("DATASYNC_ID",void 0))return F("DATASYNC_ID",void 0);throw new Xi("Datasync ID not set","unknown");}
;function $i(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function aj(a){return a.substr(0,a.indexOf(":"))||a}
;var bj={},cj=(bj.AUTH_INVALID="No user identifier specified.",bj.EXPLICIT_ABORT="Transaction was explicitly aborted.",bj.IDB_NOT_SUPPORTED="IndexedDB is not supported.",bj.MISSING_INDEX="Index not created.",bj.MISSING_OBJECT_STORES="Object stores not created.",bj.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",bj.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",bj.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
bj.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",bj.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",bj.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",bj),dj={},ej=(dj.AUTH_INVALID="ERROR",dj.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",dj.EXPLICIT_ABORT="IGNORED",dj.IDB_NOT_SUPPORTED="ERROR",dj.MISSING_INDEX="WARNING",dj.MISSING_OBJECT_STORES="ERROR",dj.DB_DELETED_BY_MISSING_OBJECT_STORES=
"WARNING",dj.QUOTA_EXCEEDED="WARNING",dj.QUOTA_MAYBE_EXCEEDED="WARNING",dj.UNKNOWN_ABORT="WARNING",dj.INCOMPATIBLE_DB_VERSION="WARNING",dj),fj={},gj=(fj.AUTH_INVALID=!1,fj.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,fj.EXPLICIT_ABORT=!1,fj.IDB_NOT_SUPPORTED=!1,fj.MISSING_INDEX=!1,fj.MISSING_OBJECT_STORES=!1,fj.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,fj.QUOTA_EXCEEDED=!1,fj.QUOTA_MAYBE_EXCEEDED=!0,fj.UNKNOWN_ABORT=!0,fj.INCOMPATIBLE_DB_VERSION=!1,fj);
function O(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?cj[a]:c;d=void 0===d?ej[a]:d;e=void 0===e?gj[a]:e;Xi.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,O.prototype)}
v(O,Xi);function hj(a,b){O.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},cj.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,hj.prototype)}
v(hj,O);function ij(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,ij.prototype)}
v(ij,Error);var jj=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function kj(a,b,c,d){b=aj(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof O)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new O("QUOTA_EXCEEDED",a);if(Hc&&"UnknownError"===e.name)return new O("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof ij)return new O("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&jj.some(function(f){return e.message.includes(f)}))return new O("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new O("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",Ym:e.name})];e.level="WARNING";return e}
function lj(a,b,c){var d=Si();return new O("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null===d||void 0===d?void 0:d.hasSucceededOnce}})}
;function mj(a){if(!a)throw Error();throw a;}
function nj(a){return a}
function oj(a){this.h=a}
function R(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
R.all=function(a){return new R(new oj(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ja:0};f.ja<a.length;f={ja:f.ja},++f.ja)pj(R.resolve(a[f.ja]).then(function(g){return function(h){d[g.ja]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
R.resolve=function(a){return new R(new oj(function(b,c){a instanceof R?a.then(b,c):b(a)}))};
R.reject=function(a){return new R(new oj(function(b,c){c(a)}))};
R.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:nj,e=null!==b&&void 0!==b?b:mj;return new R(new oj(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){qj(c,c,d,f,g)}),c.onRejected.push(function(){rj(c,c,e,f,g)})):"FULFILLED"===c.state.status?qj(c,c,d,f,g):"REJECTED"===c.state.status&&rj(c,c,e,f,g)}))};
function pj(a,b){a.then(void 0,b)}
function qj(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof R?sj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function rj(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof R?sj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function sj(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof R?sj(a,b,f,d,e):d(f)},function(f){e(f)})}
;function tj(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function uj(a){return new Promise(function(b,c){tj(a,b,c)})}
function T(a){return new R(new oj(function(b,c){tj(a,b,c)}))}
;function vj(a,b){return new R(new oj(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function wj(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(N());this.i=!1}
m=wj.prototype;m.add=function(a,b,c){return xj(this,[a],{mode:"readwrite",M:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return xj(this,[a],{mode:"readwrite",M:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return xj(this,[a],{mode:"readonly",M:!0},function(c){return c.objectStore(a).count(b)})};
function yj(a,b,c){a=a.h.createObjectStore(b,c);return new zj(a)}
m.delete=function(a,b){return xj(this,[a],{mode:"readwrite",M:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return xj(this,[a],{mode:"readonly",M:!0},function(c){return c.objectStore(a).get(b)})};
function Aj(a,b){return xj(a,["LogsRequestsStore"],{mode:"readwrite",M:!0},function(c){c=c.objectStore("LogsRequestsStore");return T(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function xj(a,b,c,d){var e,f,g,h,k,l,n,p,t,q,z,A;return x(function(H){switch(H.h){case 1:var P={mode:"readonly",M:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?P.mode=c:Object.assign(P,c);e=P;a.transactionCount++;f=e.M?3:1;g=0;case 2:if(h){H.A(3);break}g++;k=Math.round(N());ra(H,4);l=a.h.transaction(b,e.mode);P=new Bj(l);P=Cj(P,d);return w(H,P,6);case 6:return n=H.i,p=Math.round(N()),Dj(a,k,p,g,void 0,b.join(),e),H.return(n);case 4:t=sa(H);q=Math.round(N());z=kj(t,a.h.name,b.join(),a.h.version);
if((A=z instanceof O&&!z.h)||g>=f)Dj(a,k,q,g,z,b.join(),e),h=z;H.A(2);break;case 3:return H.return(Promise.reject(h))}})}
function Dj(a,b,c,d,e,f,g){b=c-b;e?(e instanceof O&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&Wi("QUOTA_EXCEEDED",{dbName:aj(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof O&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),Wi("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Ej(a,!1,d,f,b,g.tag),Vi(e)):Ej(a,!0,d,f,b,g.tag)}
function Ej(a,b,c,d,e,f){Wi("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function zj(a){this.h=a}
m=zj.prototype;m.add=function(a,b){return T(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return T(this.h.clear()).then(function(){})};
m.count=function(a){return T(this.h.count(a))};
function Fj(a,b){return Gj(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?Fj(this,a):T(this.h.delete(a))};
m.get=function(a){return T(this.h.get(a))};
m.index=function(a){try{return new Hj(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new ij(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function Gj(a,b,c){a=a.h.openCursor(b.query,b.direction);return Ij(a).then(function(d){return vj(d,c)})}
function Bj(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=O;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Cj(a,b){var c=new Promise(function(d,e){try{pj(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
Bj.prototype.abort=function(){this.h.abort();this.i=!0;throw new O("EXPLICIT_ABORT");};
Bj.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new zj(a),this.j.set(a,b));return b};
function Hj(a){this.h=a}
m=Hj.prototype;m.count=function(a){return T(this.h.count(a))};
m.delete=function(a){return Jj(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return T(this.h.get(a))};
m.getKey=function(a){return T(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Jj(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Ij(a).then(function(d){return vj(d,c)})}
function Kj(a,b){this.request=a;this.cursor=b}
function Ij(a){return T(a).then(function(b){return b?new Kj(a,b):null})}
m=Kj.prototype;m.advance=function(a){this.cursor.advance(a);return Ij(this.request)};
m.continue=function(a){this.cursor.continue(a);return Ij(this.request)};
m.delete=function(){return T(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.getValue=function(){return this.cursor.value};
m.update=function(a){return T(this.cursor.update(a))};function Lj(a,b,c){return new Promise(function(d,e){function f(){t||(t=new wj(g.result,{closed:p}));return t}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.Yb,n=c.upgrade,p=c.closed,t;g.addEventListener("upgradeneeded",function(q){try{if(null===q.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");q.dataLoss&&"none"!==q.dataLoss&&Wi("IDB_DATA_CORRUPTED",{reason:q.dataLossMessage||"unknown reason",dbName:aj(a)});var z=f(),A=new Bj(g.transaction);
n&&n(z,function(H){return q.oldVersion<H&&q.newVersion>=H},A);
A.done.catch(function(H){e(H)})}catch(H){e(H)}});
g.addEventListener("success",function(){var q=g.result;k&&q.addEventListener("versionchange",function(){k(f())});
q.addEventListener("close",function(){Wi("IDB_UNEXPECTEDLY_CLOSED",{dbName:aj(a),dbVersion:q.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Mj(a,b,c){c=void 0===c?{}:c;return Lj(a,b,c)}
function Nj(a,b){b=void 0===b?{}:b;var c,d,e;return x(function(f){c=self.indexedDB.deleteDatabase(a);d=b;(e=d.blocked)&&c.addEventListener("blocked",function(){e()});
return w(f,uj(c),0)})}
;function Oj(a,b){this.name=a;this.options=b;this.l=!0;this.j=!1}
Oj.prototype.i=function(a,b,c){c=void 0===c?{}:c;return Mj(a,b,c)};
Oj.prototype.delete=function(a){a=void 0===a?{}:a;return Nj(this.name,a)};
function Pj(a,b){return new O("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Qj(a,b){if(!b)throw lj("openWithToken",aj(a.name));return a.open()}
Oj.prototype.open=function(){function a(){var f,g,h,k,l,n,p,t,q,z;return x(function(A){switch(A.h){case 1:return h=null!==(f=Error().stack)&&void 0!==f?f:"",ra(A,2),w(A,c.i(c.name,c.options.version,e),4);case 4:k=A.i;for(var H=c.options,P=[],Q=u(Object.keys(H.ra)),S=Q.next();!S.done;S=Q.next()){S=S.value;var Ec=H.ra[S],If=void 0===Ec.Pb?Number.MAX_VALUE:Ec.Pb;!(k.h.version>=Ec.Ka)||k.h.version>=If||k.h.objectStoreNames.contains(S)||P.push(S)}l=P;if(0===l.length){A.A(5);break}n=Object.keys(c.options.ra);
p=k.objectStoreNames();if(c.j){A.A(6);break}c.j=!0;return w(A,c.delete(),7);case 7:return Vi(new O("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:n,foundObjectStores:p})),A.return(a());case 6:throw new hj(p,n);case 5:return A.return(k);case 2:t=sa(A);if(t instanceof DOMException?"VersionError"!==t.name:"DOMError"in self&&t instanceof DOMError?"VersionError"!==t.name:!(t instanceof Object&&"message"in t)||"An attempt was made to open a database using a lower version than the existing version."!==
t.message){A.A(8);break}return w(A,c.i(c.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),9);case 9:q=A.i;z=q.h.version;if(void 0!==c.options.version&&z>c.options.version+1)throw q.close(),c.l=!1,Pj(c,z);return A.return(q);case 8:throw b(),t instanceof Error&&!M("ytidb_async_stack_killswitch")&&(t.stack=t.stack+"\n"+h.substring(h.indexOf("\n")+1)),kj(t,c.name,"",null!==(g=c.options.version)&&void 0!==g?g:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw Pj(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,Yb:b,upgrade:this.options.upgrade};return this.h=d=a()};var Rj=new Oj("YtIdbMeta",{ra:{databases:{Ka:1}},upgrade:function(a,b){b(1)&&yj(a,"databases",{keyPath:"actualName"})}});
function Sj(a,b){var c;return x(function(d){if(1==d.h)return w(d,Qj(Rj,b),2);c=d.i;return d.return(xj(c,["databases"],{M:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return T(f.h.put(a,void 0)).then(function(){})})}))})}
function Tj(a,b){var c;return x(function(d){if(1==d.h)return a?w(d,Qj(Rj,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function Uj(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],w(e,Qj(Rj,b),2)):3!=e.h?(d=e.i,w(e,xj(d,["databases"],{M:!0,mode:"readonly"},function(f){c.length=0;return Gj(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function Vj(a){return Uj(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var Wj,Xj=new function(){}(new function(){});
function Yj(){var a,b,c;return x(function(d){switch(d.h){case 1:a=Si();if(null===a||void 0===a?0:a.hasSucceededOnce)return d.return(!0);var e;if(e=Kh)e=/WebKit\/([0-9]+)/.exec(Tb),e=!!(e&&600<=parseInt(e[1],10));e&&(e=/WebKit\/([0-9]+)/.exec(Tb),e=!(e&&602<=parseInt(e[1],10)));if(e||rc)return d.return(!1);try{if(b=self,!(b.indexedDB&&b.IDBIndex&&b.IDBKeyRange&&b.IDBObjectStore))return d.return(!1)}catch(f){return d.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return d.return(!1);
ra(d,2);c={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(d,Sj(c,Xj),4);case 4:return w(d,Tj("yt-idb-test-do-not-use",Xj),5);case 5:return d.return(!0);case 2:return sa(d),d.return(!1)}})}
function Zj(){if(void 0!==Wj)return Wj;Ui=!0;return Wj=Yj().then(function(a){Ui=!1;var b,c;null!==(b=Ri())&&void 0!==b&&b.h&&(b=Si(),b={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a},null===(c=Ri())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0));return a})}
function ak(){return C("ytglobal.idbToken_")||void 0}
function bk(){var a=ak();return a?Promise.resolve(a):Zj().then(function(b){(b=b?Xj:void 0)&&B("ytglobal.idbToken_",b,void 0);return b})}
;new function(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})};function ck(a){if(!Yi())throw a=new O("AUTH_INVALID",{dbName:a}),Vi(a),a;var b=Zi();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function dk(a,b,c,d){var e,f,g,h,k,l;return x(function(n){switch(n.h){case 1:return f=null!==(e=Error().stack)&&void 0!==e?e:"",w(n,bk(),2);case 2:g=n.i;if(!g)throw h=lj("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),Vi(h),h;$i(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:ck(a);ra(n,3);return w(n,Sj(k,g),5);case 5:return w(n,Mj(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=sa(n),ra(n,7),w(n,Tj(k.actualName,
g),9);case 9:n.h=8;n.m=0;break;case 7:sa(n);case 8:throw l;}})}
function ek(a,b,c){c=void 0===c?{}:c;return dk(a,b,!1,c)}
function fk(a,b,c){c=void 0===c?{}:c;return dk(a,b,!0,c)}
function gk(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return w(e,bk(),2);if(3!=e.h){c=e.i;if(!c)return e.return();$i(a);d=ck(a);return w(e,Nj(d.actualName,b),3)}return w(e,Tj(d.actualName,c),0)})}
function hk(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?w(e,Nj(d.actualName,b),2):w(e,Tj(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function ik(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return w(d,bk(),2);if(3!=d.h){b=d.i;if(!b)return d.return();$i("LogsDatabaseV2");return w(d,Vj(b),3)}c=d.i;return w(d,hk(c,a,b),0)})}
function jk(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return w(d,bk(),2);if(3!=d.h){c=d.i;if(!c)return d.return();$i(a);return w(d,Nj(a,b),3)}return w(d,Tj(a,c),0)})}
;function kk(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.na=function(){};
this.now=Date.now;this.qa=!1;this.sb=null!==(b=a.sb)&&void 0!==b?b:100;this.qb=null!==(c=a.qb)&&void 0!==c?c:1;this.ob=null!==(d=a.ob)&&void 0!==d?d:2592E6;this.mb=null!==(e=a.mb)&&void 0!==e?e:12E4;this.pb=null!==(f=a.pb)&&void 0!==f?f:5E3;this.C=null!==(g=a.C)&&void 0!==g?g:void 0;this.Ba=!!a.Ba;this.za=null!==(h=a.za)&&void 0!==h?h:.1;this.Fa=null!==(k=a.Fa)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.na&&(this.na=a.na);a.qa&&(this.qa=a.qa);this.D=a.D;this.P=a.P;this.J=a.J;
this.K=a.K;this.W=a.W;this.Va=a.Va;this.Ua=a.Ua;this.C&&(!this.D||this.D("networkless_logging"))&&lk(this)}
function lk(a){x(function(b){if(1==b.h)return!a.C||a.qa?b.return():a.Ba&&Math.random()<=a.za?w(b,a.J.xb(a.C),2):b.A(2);mk(a);a.K.I()&&a.ta();a.K.U(a.Va,a.ta.bind(a));a.K.U(a.Ua,a.bb.bind(a));a.h=!0;b.h=0})}
m=kk.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.C&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.J.set(d,this.C).then(function(e){d.id=e;c.K.I()&&nk(c,d)}).catch(function(e){nk(c,d);
ok(c,e)})}else this.W(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.C&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.D&&this.D("nwl_skip_retry")&&(e.skipRetry=c);if(this.K.I()||this.D&&this.D("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return w(k,d.J.set(e,d.C).catch(function(l){ok(d,l)}),2);
f(g,h);k.h=0})}}this.W(a,b,e.skipRetry)}else this.J.set(e,this.C).catch(function(g){d.W(a,b,e.skipRetry);
ok(d,g)})}else this.W(a,b,this.D&&this.D("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.C&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.J.ma(d.id,c.C):e=!0;c.K.ea&&c.D&&c.D("vss_network_hint")&&c.K.ea(!0);f(g,h)};
this.W(d.url,d.options);this.J.set(d,this.C).then(function(g){d.id=g;e&&c.J.ma(d.id,c.C)}).catch(function(g){ok(c,g)})}else this.W(a,b)};
m.ta=function(){var a=this;if(!this.C)throw lj("throttleSend");this.i||(this.i=this.P.L(function(){var b;return x(function(c){if(1==c.h)return w(c,a.J.ib("NEW",a.C),2);if(3!=c.h)return b=c.i,b?w(c,nk(a,b),3):(a.bb(),c.return());a.i&&(a.i=0,a.ta());c.h=0})},this.sb))};
m.bb=function(){this.P.aa(this.i);this.i=0};
function nk(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!a.C)throw c=lj("immediateSend"),c;if(void 0===b.id){e.A(2);break}return w(e,a.J.Jb(b.id,a.C),3);case 3:(d=e.i)?b=d:a.na(Error("The request cannot be found in the database."));case 2:if(pk(a,b,a.ob)){e.A(4);break}a.na(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.A(5);break}return w(e,a.J.ma(b.id,a.C),5);case 5:return e.return();case 4:b.skipRetry||(b=qk(a,b));if(!b){e.A(0);break}if(!b.skipRetry||
void 0===b.id){e.A(8);break}return w(e,a.J.ma(b.id,a.C),8);case 8:a.W(b.url,b.options,!!b.skipRetry),e.h=0}})}
function qk(a,b){if(!a.C)throw lj("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:g=rk(f);if(!(a.D&&a.D("nwl_consider_error_code")&&g||a.D&&!a.D("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.Fa)){h.A(2);break}if(!a.K.X){h.A(3);break}return w(h,a.K.X(),3);case 3:if(a.K.I()){h.A(2);break}c(e,f);if(!a.D||!a.D("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){h.A(6);break}return w(h,a.J.Wa(b.id,a.C,!1),6);case 6:return h.return();case 2:if(a.D&&a.D("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.Fa)return h.return();a.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){h.A(8);break}return b.sendCount<a.qb?w(h,a.J.Wa(b.id,a.C),12):w(h,a.J.ma(b.id,a.C),8);case 12:a.P.L(function(){a.K.I()&&a.ta()},a.pb);
case 8:c(e,f),h.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return void 0===(null===b||void 0===b?void 0:b.id)?g.A(2):w(g,a.J.ma(b.id,a.C),2);a.K.ea&&a.D&&a.D("vss_network_hint")&&a.K.ea(!0);d(e,f);g.h=0})};
return b}
function pk(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function mk(a){if(!a.C)throw lj("retryQueuedRequests");a.J.ib("QUEUED",a.C).then(function(b){b&&!pk(a,b,a.mb)?a.P.L(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.A(2):w(c,a.J.Wa(b.id,a.C),2);mk(a);c.h=0})}):a.K.I()&&a.ta()})}
function ok(a,b){a.tb&&!a.K.I()?a.tb(b):a.handleError(b)}
function rk(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function sk(a,b){this.version=a;this.args=b}
;function tk(a,b){this.topic=a;this.h=b}
tk.prototype.toString=function(){return this.topic};var uk=C("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.oa;K.prototype.publish=K.prototype.ha;K.prototype.clear=K.prototype.clear;B("ytPubsub2Pubsub2Instance",uk,void 0);var vk=C("ytPubsub2Pubsub2SubscribedKeys")||{};B("ytPubsub2Pubsub2SubscribedKeys",vk,void 0);var wk=C("ytPubsub2Pubsub2TopicToKeys")||{};B("ytPubsub2Pubsub2TopicToKeys",wk,void 0);var xk=C("ytPubsub2Pubsub2IsAsync")||{};B("ytPubsub2Pubsub2IsAsync",xk,void 0);
B("ytPubsub2Pubsub2SkipSubKey",null,void 0);function yk(a,b){var c=zk();c&&c.publish.call(c,a.toString(),a,b)}
function Ak(a){var b=Bk,c=zk();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=C("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(vk[d])try{if(f&&b instanceof tk&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.ga){var l=new h;h.ga=l.version}var n=h.ga}catch(p){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
fb(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){zg(p)}},xk[b.toString()]?C("yt.scheduler.instance")?$g.L(g):Sg(g,0):g())});
vk[d]=!0;wk[b.toString()]||(wk[b.toString()]=[]);wk[b.toString()].push(d);return d}
function Ck(){var a=Dk,b=Ak(function(c){a.apply(void 0,arguments);Ek(b)});
return b}
function Ek(a){var b=zk();b&&("number"===typeof a&&(a=[a]),E(a,function(c){b.unsubscribeByKey(c);delete vk[c]}))}
function zk(){return C("ytPubsub2Pubsub2Instance")}
;function Fk(a,b){Oj.call(this,a,b);this.options=b;$i(a)}
v(Fk,Oj);function Gk(a,b){var c;return function(){c||(c=new Fk(a,b));return c}}
Fk.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.Xa?fk:ek)(a,b,Object.assign({},c))};
Fk.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Xa?jk:gk)(this.name,a)};
function Hk(a,b){return Gk(a,b)}
;var Ik;
function Jk(){if(Ik)return Ik();var a={};Ik=Hk("LogsDatabaseV2",{ra:(a.LogsRequestsStore={Ka:2},a),Xa:!1,upgrade:function(b,c,d){c(2)&&yj(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Ik()}
;function Kk(a){return Qj(Jk(),a)}
function Lk(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:N(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,Kk(b),2);if(3!=g.h)return d=g.i,e=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:F("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,Aj(d,e),3);f=g.i;c.Zb=N();Mk(c);return g.return(f)})}
function Nk(a,b){var c,d,e,f,g,h,k;return x(function(l){if(1==l.h)return c={startTime:N(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(l,Kk(b),2);if(3!=l.h)return d=l.i,e=F("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,N()],h=IDBKeyRange.bound(f,g),k=void 0,w(l,xj(d,["LogsRequestsStore"],{mode:"readwrite",M:!0},function(n){return Jj(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.getValue()&&(k=p.getValue(),"NEW"===a&&(k.status="QUEUED",
p.update(k)))})}),3);
c.Zb=N();Mk(c);return l.return(k)})}
function Ok(a,b){var c;return x(function(d){if(1==d.h)return w(d,Kk(b),2);c=d.i;return d.return(xj(c,["LogsRequestsStore"],{mode:"readwrite",M:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",T(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Pk(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.h)return w(e,Kk(b),2);d=e.i;return e.return(xj(d,["LogsRequestsStore"],{mode:"readwrite",M:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),T(g.h.put(h,void 0)).then(function(){return h})):R.resolve(void 0)})}))})}
function Qk(a,b){var c;return x(function(d){if(1==d.h)return w(d,Kk(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Rk(a){var b,c;return x(function(d){if(1==d.h)return w(d,Kk(a),2);b=d.i;c=N()-2592E6;return w(d,xj(b,["LogsRequestsStore"],{mode:"readwrite",M:!0},function(e){return Gj(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Sk(){return x(function(a){return w(a,ik(),0)})}
function Mk(a){M("nwl_csi_killswitch")||.01>=Math.random()&&yk("nwl_transaction_latency_payload",a)}
;var Tk={},Uk=Hk("ServiceWorkerLogsDatabase",{ra:(Tk.SWHealthLog={Ka:1},Tk),Xa:!0,upgrade:function(a,b){b(1)&&yj(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Vk(a){return Qj(Uk(),a)}
function Wk(a){var b,c;return x(function(d){if(1==d.h)return w(d,Vk(a),2);b=d.i;c=N()-2592E6;return w(d,xj(b,["SWHealthLog"],{mode:"readwrite",M:!0},function(e){return Gj(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Xk(a){var b;return x(function(c){if(1==c.h)return w(c,Vk(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;var Yk;function Zk(){Yk||(Yk=new Li("yt.offline"));return Yk}
function $k(a){if(M("offline_error_handling")){var b=Zk().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Zk().set("errors",b,2592E3,!0)}}
function al(){if(M("offline_error_handling")){var a=Zk().get("errors",!0);if(a){for(var b in a)if(a[b]){var c=new Xi(b,"sent via offline_errors");c.name=a[b].name;c.stack=a[b].stack;c.level=a[b].level;zg(c)}Zk().set("errors",{},2592E3,!0)}}}
;var bl=Eg("network_polling_interval",3E4);function U(){J.call(this);this.H=0;this.N=this.m=!1;this.l=this.Oa();M("use_shared_nsm")?(Fe.h||(Fe.h=new Fe($g)),this.j=Fe.h):(cl(this),dl(this))}
v(U,J);function el(){if(!U.h){var a=C("yt.networkStatusManager.instance")||new U;B("yt.networkStatusManager.instance",a,void 0);U.h=a}return U.h}
m=U.prototype;m.I=function(){var a;return M("use_shared_nsm")&&this.j?null===(a=this.j)||void 0===a?void 0:a.I():this.l};
m.ea=function(a){var b;M("use_shared_nsm")&&this.j?null===(b=this.j)||void 0===b?void 0:b.j=a:a!==this.l&&(this.l=a)};
m.Kb=function(a){!M("use_shared_nsm")&&(this.m=!0,void 0===a?0:a)&&(this.H||fl(this))};
m.Oa=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.zb=function(){this.N=!0};
m.U=function(a,b){return M("use_shared_nsm")&&this.j?this.j.U(a,b):J.prototype.U.call(this,a,b)};
function dl(a){window.addEventListener("online",function(){return x(function(b){if(1==b.h)return w(b,a.X(),2);a.N&&al();b.h=0})})}
function cl(a){window.addEventListener("offline",function(){return x(function(b){return w(b,a.X(),0)})})}
function fl(a){a.H=Wg(function(){return x(function(b){if(1==b.h)return a.l?a.Oa()||!a.m?b.A(3):w(b,a.X(),3):w(b,a.X(),3);fl(a);b.h=0})},bl)}
m.X=function(a){var b=this;return M("use_shared_nsm")&&this.j?Ge(this.j,a):this.o?this.o:this.o=new Promise(function(c){var d,e,f;return x(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,ra(g,2,3),d&&(b.B=$g.L(function(){d.abort()},a||2E4)),w(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:ta(g);b.o=void 0;b.B&&$g.aa(b.B);f!==b.l&&(b.l=f,b.l&&b.m?De(b,"ytnetworkstatus-online"):b.m&&De(b,"ytnetworkstatus-offline"));c(f);ua(g);break;case 2:sa(g),f=!1,g.A(3)}})})};
U.prototype.sendNetworkCheckRequest=U.prototype.X;U.prototype.listen=U.prototype.U;U.prototype.enableErrorFlushing=U.prototype.zb;U.prototype.getWindowStatus=U.prototype.Oa;U.prototype.monitorNetworkStatusChange=U.prototype.Kb;U.prototype.networkStatusHint=U.prototype.ea;U.prototype.isNetworkAvailable=U.prototype.I;U.getInstance=el;function gl(a){a=void 0===a?{}:a;J.call(this);var b=this;this.l=this.H=0;this.m="ytnetworkstatus-offline";this.o="ytnetworkstatus-online";M("use_shared_nsm")&&(this.m="networkstatus-offline",this.o="networkstatus-online");this.j=el();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.j);c&&c(a.gb);a.Da&&!M("use_shared_nsm")&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.j))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.j))a.Ga?
(this.Ga=a.Ga,c(this.o,function(){hl(b,"publicytnetworkstatus-online");M("use_shared_nsm")&&a.Da&&al()}),c(this.m,function(){hl(b,"publicytnetworkstatus-offline")})):(c(this.o,function(){De(b,"publicytnetworkstatus-online");
M("use_shared_nsm")&&a.Da&&al()}),c(this.m,function(){De(b,"publicytnetworkstatus-offline")}))}
v(gl,J);gl.prototype.I=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.j);return a?a():!0};
gl.prototype.ea=function(a){var b=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
gl.prototype.X=function(a){var b=this,c;return x(function(d){return(c=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j))?d.return(c(a)):d.return(!0)})};
function hl(a,b){a.Ga?a.l?($g.aa(a.H),a.H=$g.L(function(){a.B!==b&&(De(a,b),a.B=b,a.l=N())},a.Ga-(N()-a.l))):(De(a,b),a.B=b,a.l=N()):De(a,b)}
;var il=!1,jl=0,kl=0,ll,ml=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:il,potentialEsfErrorCounter:kl};B("ytNetworklessLoggingInitializationOptions",ml,void 0);
function nl(){var a;x(function(b){switch(b.h){case 1:return w(b,bk(),2);case 2:a=b.i;if(!a||!Yi()&&!M("nwl_init_require_datasync_id_killswitch")){b.A(0);break}il=!0;ml.isNwlInitialized=il;return w(b,jk("LogsDatabaseV2"),4);case 4:if(!(.1>=Math.random())){b.A(5);break}return w(b,Rk(a),6);case 6:return w(b,Wk(a),5);case 5:ol();pl().I()&&ql();pl().U("publicytnetworkstatus-online",ql);pl().U("publicytnetworkstatus-offline",rl);if(!M("networkless_immediately_drop_sw_health_store")){b.A(8);break}return w(b,
sl(),8);case 8:if(M("networkless_immediately_drop_all_requests"))return w(b,Sk(),0);b.A(0)}})}
function tl(a,b){function c(d){var e=pl().I();if(!ul()||!d||e&&M("vss_networkless_bypass_write"))vl(a,b);else{var f={url:a,options:b,timestamp:N(),status:"NEW",sendCount:0};Lk(f,d).then(function(g){f.id=g;pl().I()&&wl(f)}).catch(function(g){wl(f);
pl().I()?zg(g):$k(g)})}}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?bk().then(function(d){c(d)}):c(ak())}
function xl(a,b){function c(d){if(ul()&&d){var e={url:a,options:b,timestamp:N(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?Qk(e.id,d):f=!0;M("vss_network_hint")&&pl().ea(!0);g(h,k)};
vl(e.url,e.options);Lk(e,d).then(function(h){e.id=h;f&&Qk(e.id,d)}).catch(function(h){pl().I()?zg(h):$k(h)})}else vl(a,b)}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?bk().then(function(d){c(d)}):c(ak())}
function ql(){var a=ak();if(!a)throw lj("throttleSend");jl||(jl=$g.L(function(){var b;return x(function(c){if(1==c.h)return w(c,Nk("NEW",a),2);if(3!=c.h)return b=c.i,b?w(c,wl(b),3):(rl(),c.return());jl&&(jl=0,ql());c.h=0})},100))}
function rl(){$g.aa(jl);jl=0}
function wl(a){var b,c,d;return x(function(e){switch(e.h){case 1:b=ak();if(!b)throw c=lj("immediateSend"),c;if(void 0===a.id){e.A(2);break}return w(e,Ok(a.id,b),3);case 3:(d=e.i)?a=d:Ag(Error("The request cannot be found in the database."));case 2:if(yl(a,2592E6)){e.A(4);break}Ag(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.A(5);break}return w(e,Qk(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=zl(a));var f=a,g,h;if(null===(h=null===(g=null===
f||void 0===f?void 0:f.options)||void 0===g?void 0:g.postParams)||void 0===h?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(N());a=f;if(!a){e.A(0);break}if(!a.skipRetry||void 0===a.id){e.A(8);break}return w(e,Qk(a.id,b),8);case 8:vl(a.url,a.options,!!a.skipRetry),e.h=0}})}
function zl(a){var b=ak();if(!b)throw lj("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g;return x(function(h){switch(h.h){case 1:g=rk(f);if(!(M("nwl_consider_error_code")&&g||!M("nwl_consider_error_code")&&Al()<=Eg("potential_esf_error_limit",10))){h.A(2);break}return w(h,pl().X(),3);case 3:if(pl().I()){h.A(2);break}c(e,f);if(!M("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:a.id)){h.A(5);break}return w(h,Pk(a.id,b,!1),5);case 5:return h.return();case 2:if(M("nwl_consider_error_code")&&!g&&Al()>Eg("potential_esf_error_limit",10))return h.return();
C("ytNetworklessLoggingInitializationOptions")&&ml.potentialEsfErrorCounter++;kl++;if(void 0===(null===a||void 0===a?void 0:a.id)){h.A(7);break}return 1>a.sendCount?w(h,Pk(a.id,b),11):w(h,Qk(a.id,b),7);case 11:$g.L(function(){pl().I()&&ql()},5E3);
case 7:c(e,f),h.h=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return x(function(g){if(1==g.h)return void 0===(null===a||void 0===a?void 0:a.id)?g.A(2):w(g,Qk(a.id,b),2);M("vss_network_hint")&&pl().ea(!0);d(e,f);g.h=0})};
return a}
function yl(a,b){a=a.timestamp;return N()-a>=b?!1:!0}
function ol(){var a=ak();if(!a)throw lj("retryQueuedRequests");Nk("QUEUED",a).then(function(b){b&&!yl(b,12E4)?$g.L(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.A(2):w(c,Pk(b.id,a),2);ol();c.h=0})}):pl().I()&&ql()})}
function sl(){var a,b;return x(function(c){a=ak();if(!a)throw b=lj("clearSWHealthLogsDb"),b;return c.return(Xk(a).catch(function(d){zg(d)}))})}
function pl(){ll||(ll=new gl({Da:!0,gb:!0}));return ll}
function vl(a,b,c){c&&0===Object.keys(b).length?Oh(a):Ch(a,b)}
function ul(){return C("ytNetworklessLoggingInitializationOptions")?ml.isNwlInitialized:il}
function Al(){return C("ytNetworklessLoggingInitializationOptions")?ml.potentialEsfErrorCounter:kl}
;function Bl(){kk.call(this,{J:{xb:Rk,ma:Qk,ib:Nk,Jb:Ok,Wa:Pk,set:Lk},K:new gl({Da:!0,gb:!0}),handleError:zg,na:Ag,W:Cl,now:N,tb:$k,P:Zg(),Va:"publicytnetworkstatus-online",Ua:"publicytnetworkstatus-offline",Ba:!0,za:.1,Fa:Eg("potential_esf_error_limit",10),D:M,qa:!Yi()});this.Ba&&Math.random()<=this.za&&this.C&&Wk(this.C);M("networkless_immediately_drop_sw_health_store")&&Dl(this);M("networkless_immediately_drop_all_requests")&&Sk();jk("LogsDatabaseV2")}
v(Bl,kk);function El(){var a=C("yt.networklessRequestController.instance");a||(a=new Bl,B("yt.networklessRequestController.instance",a,void 0),M("networkless_logging")&&bk().then(function(b){a.C=b;lk(a)}));
return a}
Bl.prototype.writeThenSend=function(a,b){b||(b={});Yi()||(this.h=!1);kk.prototype.writeThenSend.call(this,a,b)};
Bl.prototype.sendThenWrite=function(a,b,c){b||(b={});Yi()||(this.h=!1);kk.prototype.sendThenWrite.call(this,a,b,c)};
Bl.prototype.sendAndWrite=function(a,b){b||(b={});Yi()||(this.h=!1);kk.prototype.sendAndWrite.call(this,a,b)};
function Dl(a){var b;x(function(c){if(!a.C)throw b=lj("clearSWHealthLogsDb"),b;return c.return(Xk(a.C).catch(function(d){a.handleError(d)}))})}
function Cl(a,b,c){var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(N());c&&0===Object.keys(b).length?Oh(a):Ch(a,b)}
;function Fl(a){var b=this;this.config_=null;a?this.config_=a:Ii()&&(this.config_=si());Wg(function(){Qi(b)},5E3)}
Fl.prototype.isReady=function(){!this.config_&&Ii()&&(this.config_=si());return!!this.config_};
function vi(a,b,c,d){function e(z){z=void 0===z?!1:z;var A;if(d.retry&&"www.youtube-nocookie.com"!=h&&(z||M("skip_ls_gel_retry")||(A=Oi(b,c,l,k)),A)){var H=g.onSuccess,P=g.onFetchSuccess;g.onSuccess=function(Q,S){Pi(A);H(Q,S)};
c.onFetchSuccess=function(Q,S){Pi(A);P(Q,S)}}try{z&&d.retry&&!d.lb.bypassNetworkless?(g.method="POST",d.lb.writeThenSend?M("use_new_nwl")?El().writeThenSend(q,g):tl(q,g):M("use_new_nwl")?El().sendAndWrite(q,g):xl(q,g)):(g.method="POST",g.postParams||(g.postParams={}),Ch(q,g))}catch(Q){if("InvalidAccessError"==Q.name)A&&(Pi(A),A=0),Ag(Error("An extension is blocking network request."));
else throw Q;}A&&Wg(function(){Qi(a)},5E3)}
!F("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Ag(new Xi("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new Xi("innertube xhrclient not ready",b,c,d);zg(f);throw f;}var g={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(z,A){if(d.onSuccess)d.onSuccess(A)},
onFetchSuccess:function(z){if(d.onSuccess)d.onSuccess(z)},
onError:function(z,A){if(d.onError)d.onError(A)},
onFetchError:function(z){if(d.onError)d.onError(z)},
timeout:d.timeout,withCredentials:!0},h="";(f=a.config_.Gb)&&(h=f);var k=a.config_.Ib||!1,l=Ji(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},t=a.config_.Hb&&f;M("omit_innertube_api_key_for_bearer_auth_header")&&(t=t&&f.startsWith("Bearer"));t||(p.key=a.config_.innertubeApiKey);var q=qh(""+h+n,p||{},!0);M("use_new_nwl")||ul()?Zj().then(function(z){e(z)}):e(!1)}
;function V(a,b,c){c=void 0===c?{}:c;var d=Fl;F("ytLoggingEventsDefaultDisabled",!1)&&Fl==Fl&&(d=null);xi(a,b,d,c)}
;var Gl=[{Ta:function(a){return"Cannot read property '"+a.key+"'"},
Ea:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ta:function(a){return"Cannot call '"+a.key+"'"},
Ea:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ta:function(a){return a.key+" is not defined"},
Ea:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Il={da:[],Z:[{ab:Hl,weight:500}]};function Hl(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Jl(){this.Z=[];this.da=[]}
var Kl;function Ll(){if(!Kl){var a=Kl=new Jl;a.da.length=0;a.Z.length=0;Il.da&&a.da.push.apply(a.da,Il.da);Il.Z&&a.Z.push.apply(a.Z,Il.Z)}return Kl}
;var Ml=new K;function Nl(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Ol(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Ol(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Ol(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Ol(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Pl(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Ql(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Nl(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Ql(e+".ve",f,g,h):0;d+=g;d+=Ql(e,a[e],b,c);if(500<d)break}}else c[b]=Rl(a),d+=c[b].length;else c[b]=Rl(a),d+=c[b].length;return d}
function Ql(a,b,c,d){c+="."+a;a=Rl(b);d[c]=a;return c.length+a.length}
function Rl(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Sl=new Set,Tl=0,Ul=0,Vl=0,Wl=[],Xl=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Yl(a){Zl(a,"WARNING")}
function Zl(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||F("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||F("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;if(a&&(a.hasOwnProperty("level")&&a.level&&(b=a.level),M("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),a.hasOwnProperty("args")&&d.push("Error args: "+JSON.stringify(a.args)),d.push("File name: "+
a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),!(5<=Tl))){var g=be(a);d=g.message||"Unknown Error";e=g.name||"UnknownError";var h=g.stack||a.i||"Not available";h.startsWith(e+": "+d)&&(f=h.split("\n"),f.shift(),h=f.join("\n"));f=g.lineNumber||"Not available";g=g.fileName||"Not available";var k=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var l=0;l<a.args.length&&!(k=Pl(a.args[l],"params."+l,c,k),500<=k);l++);else if(a.hasOwnProperty("params")&&a.params){var n=
a.params;if("object"===typeof a.params)for(l in n){if(n[l]){var p="params."+l,t=Rl(n[l]);c[p]=t;k+=p.length+t.length;if(500<k)break}}else c.params=Rl(n)}if(Wl.length)for(l=0;l<Wl.length&&!(k=Pl(Wl[l],"params.context."+l,c,k),500<=k);l++);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c["device.vendor"]=navigator.vendor);l={message:d,name:e,lineNumber:f,fileName:g,stack:h,params:c,sampleWeight:1};c=Number(a.columnNumber);isNaN(c)||(l.lineNumber=l.lineNumber+":"+c);if("IGNORED"===a.level)a=0;else a:{a=
Ll();c=u(a.da);for(d=c.next();!d.done;d=c.next())if(d=d.value,l.message&&l.message.match(d.Xm)){a=d.weight;break a}a=u(a.Z);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.ab(l)){a=c.weight;break a}a=1}l.sampleWeight=a;a=u(Gl);for(c=a.next();!c.done;c=a.next())if(c=c.value,c.Ea[l.name])for(e=u(c.Ea[l.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=l.message.match(f.regexp)){l.params["params.error.original"]=d[0];e=f.groups;f={};for(g=0;g<e.length;g++)f[e[g]]=d[g+1],l.params["params.error."+e[g]]=
d[g+1];l.message=c.Ta(f);break}l.params||(l.params={});a=Ll();l.params["params.errorServiceSignature"]="msg="+a.da.length+"&cb="+a.Z.length;l.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(l.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));wb("sample").constructor!==ub&&(l.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(l);if(0!==l.sampleWeight&&!Sl.has(l.message)){"ERROR"===b?
(Ml.ha("handleError",l),M("record_app_crashed_web")&&0===Vl&&1===l.sampleWeight&&(Vl++,V("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),Ul++):"WARNING"===b&&Ml.ha("handleWarning",l);if(M("kevlar_gel_error_routing")){a=b;b:{c=u(Xl);for(d=c.next();!d.done;d=c.next())if(Lh(d.value.toLowerCase())){c=!0;break b}c=!1}if(c)c=void 0;else{d={stackTrace:l.stack};l.fileName&&(d.filename=l.fileName);c=l.lineNumber&&l.lineNumber.split?l.lineNumber.split(":"):[];0!==c.length&&(1!==c.length||isNaN(Number(c[0]))?
2!==c.length||isNaN(Number(c[0]))||isNaN(Number(c[1]))||(d.lineNumber=Number(c[0]),d.columnNumber=Number(c[1])):d.lineNumber=Number(c[0]));c={level:"ERROR_LEVEL_UNKNOWN",message:l.message,errorClassName:l.name,sampleWeight:l.sampleWeight};"ERROR"===a?c.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(c.level="ERROR_LEVEL_WARNNING");d={isObfuscated:!0,browserStackInfo:d};e={pageUrl:window.location.href,kvPairs:[]};F("FEXP_EXPERIMENTS")&&(e.experimentIds=F("FEXP_EXPERIMENTS"));f=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",
void 0);g=tg.EXPERIMENT_FLAGS;if((!g||!g.web_disable_gel_stp_ecatcher_killswitch)&&f)for(h=u(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:g,value:String(f[g])});if(f=l.params)for(h=u(Object.keys(f)),g=h.next();!g.done;g=h.next())g=g.value,e.kvPairs.push({key:"client."+g,value:String(f[g])});f=F("SERVER_NAME",void 0);g=F("SERVER_VERSION",void 0);f&&g&&(e.kvPairs.push({key:"server.name",value:f}),e.kvPairs.push({key:"server.version",value:g}));c={errorMetadata:e,stackTrace:d,
logMessage:c}}c&&(V("clientError",c),("ERROR"===a||M("errors_flush_gel_always_killswitch"))&&ni())}if(!M("suppress_error_204_logging")){a=l.params||{};b={urlParams:{a:"logerror",t:"jserror",type:l.name,msg:l.message.substr(0,250),line:l.lineNumber,level:b,"client.name":a.name},postParams:{url:F("PAGE_NAME",window.location.href),file:l.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.postParams){l.stack&&(b.postParams.stack=l.stack);c=u(Object.keys(a));for(d=c.next();!d.done;d=
c.next())d=d.value,b.postParams["client."+d]=a[d];if(a=F("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(c=u(Object.keys(a)),d=c.next();!d.done;d=c.next())d=d.value,b.postParams[d]=a[d];a=F("SERVER_NAME",void 0);c=F("SERVER_VERSION",void 0);a&&c&&(b.postParams["server.name"]=a,b.postParams["server.version"]=c)}Ch(F("ECATCHER_REPORT_HOST","")+"/error_204",b)}try{Sl.add(l.message)}catch(q){}Tl++}}}
function $l(a){var b=Da.apply(1,arguments),c=a;c.args||(c.args=[]);c.args.push.apply(c.args,fa(b))}
;var am={Nc:3611,ac:27686,cc:85013,dc:23462,fc:42016,hc:62407,ic:26926,ec:43781,jc:51236,kc:79148,lc:50160,mc:77504,Ac:87907,Bc:18630,Cc:54445,Dc:80935,Ec:105675,Fc:37521,Gc:47786,Hc:98349,Ic:123695,Jc:6827,Kc:29434,Lc:7282,Mc:124448,Qc:32276,Pc:76278,Rc:93911,Sc:106531,Tc:27259,Uc:27262,Vc:27263,Xc:21759,Yc:27107,Zc:62936,bd:49568,cd:38408,dd:80637,ed:68727,fd:68728,gd:80353,hd:80356,jd:74610,kd:45707,ld:83962,md:83970,nd:46713,od:89711,pd:74612,qd:93265,rd:74611,sd:131380,ud:128979,vd:139311,wd:128978,
td:131391,xd:105350,zd:139312,Ad:134800,yd:131392,Cd:113533,Dd:93252,Ed:99357,Gd:94521,Hd:114252,Id:113532,Jd:94522,Fd:94583,Kd:88E3,Ld:139580,Md:93253,Nd:93254,Od:94387,Pd:94388,Qd:93255,Rd:97424,Bd:72502,Sd:110111,Td:76019,Vd:117092,Wd:117093,Ud:89431,Xd:110466,Yd:77240,Zd:60508,ae:137401,be:137402,ce:137046,de:73393,ee:113534,ge:92098,he:131381,ie:84517,je:83759,ke:80357,le:86113,me:72598,ne:72733,oe:107349,pe:124275,qe:118203,re:133275,se:133274,te:133272,ue:133273,we:133276,ye:117431,xe:133797,
ze:128572,Ae:133405,Be:117429,Ce:117430,De:117432,Ee:120080,Fe:117259,Ge:121692,He:132972,Ie:133051,Je:133658,Ke:132971,Le:97615,Me:31402,Oe:133624,Pe:133623,Qe:133622,Ne:133621,Re:84774,Se:95117,Te:98930,Ue:98931,Ve:98932,We:43347,Xe:129889,Ye:45474,Ze:100352,af:84758,bf:98443,cf:117985,df:74613,ef:74614,ff:64502,gf:136032,hf:74615,jf:74616,kf:122224,lf:74617,mf:77820,nf:74618,pf:93278,qf:93274,rf:93275,sf:93276,tf:22110,uf:29433,vf:133798,wf:132295,yf:120541,Af:82047,Bf:113550,Cf:75836,Df:75837,
Ef:42352,Ff:84512,Gf:76065,Hf:75989,If:16623,Jf:32594,Kf:27240,Lf:32633,Mf:74858,Of:3945,Nf:16989,Pf:45520,Qf:25488,Rf:25492,Sf:25494,Tf:55760,Uf:14057,Vf:18451,Wf:57204,Xf:57203,Yf:17897,Zf:57205,ag:18198,cg:17898,dg:17909,eg:43980,fg:46220,gg:11721,hg:49954,ig:96369,jg:3854,kg:56251,lg:25624,mg:16906,ng:99999,og:68172,pg:27068,qg:47973,rg:72773,sg:26970,tg:26971,ug:96805,vg:17752,wg:73233,xg:109512,yg:22256,zg:14115,Ag:22696,Bg:89278,Cg:89277,Dg:109513,Eg:43278,Fg:43459,Gg:43464,Hg:89279,Ig:43717,
Jg:55764,Kg:22255,Lg:89281,Mg:40963,Ng:43277,Og:43442,Pg:91824,Qg:120137,Rg:96367,Sg:36850,Tg:72694,Ug:37414,Vg:36851,Xg:124863,Wg:121343,Yg:73491,Zg:54473,ah:43375,bh:46674,dh:139095,eh:32473,fh:72901,gh:72906,hh:50947,ih:50612,jh:50613,kh:50942,lh:84938,mh:84943,nh:84939,oh:84941,ph:84944,qh:84940,rh:84942,sh:35585,th:51926,uh:79983,vh:63238,wh:18921,xh:63241,yh:57893,zh:41182,Ah:135732,Bh:33424,Ch:22207,Dh:42993,Eh:36229,Fh:22206,Gh:22205,Hh:18993,Ih:19001,Jh:18990,Kh:18991,Lh:18997,Mh:18725,Nh:19003,
Oh:36874,Ph:44763,Qh:33427,Rh:67793,Sh:22182,Th:37091,Uh:34650,Vh:50617,Wh:47261,Xh:22287,Yh:25144,Zh:97917,ai:62397,bi:125598,ci:137935,di:36961,fi:108035,gi:27426,hi:27857,ii:27846,ji:27854,ki:69692,li:61411,mi:39299,ni:38696,oi:62520,ri:36382,si:108701,ti:50663,vi:36387,wi:14908,xi:37533,yi:105443,zi:61635,Ai:62274,Bi:133818,Ci:65702,Di:65703,Ei:65701,Fi:76256,Gi:37671,Hi:49953,Ji:36216,Ki:28237,Li:39553,Mi:29222,Ni:26107,Oi:38050,Pi:26108,Ri:120745,Qi:26109,Si:26110,Ti:66881,Ui:28236,Vi:14586,
Wi:57929,Xi:74723,Yi:44098,Zi:44099,cj:23528,dj:61699,aj:134104,bj:134103,ej:59149,fj:101951,gj:97346,hj:118051,ij:95102,jj:64882,kj:119505,lj:63595,mj:63349,nj:95101,oj:75240,pj:27039,qj:68823,rj:21537,sj:83464,tj:75707,uj:83113,vj:101952,wj:101953,yj:79610,zj:125755,Aj:24402,Bj:24400,Cj:32925,Dj:57173,Ej:122502,Fj:138480,Gj:64423,Hj:64424,Ij:33986,Jj:100828,Kj:129089,Lj:21409,Pj:135155,Qj:135156,Rj:135157,Sj:135158,Tj:135159,Uj:135160,Vj:135161,Wj:135162,Xj:135163,Yj:135164,Zj:135165,ak:135166,
Mj:11070,Nj:11074,Oj:17880,bk:14001,dk:30709,ek:30707,fk:30711,gk:30710,hk:30708,ck:26984,ik:63648,jk:63649,kk:51879,lk:111059,mk:5754,nk:20445,qk:130975,pk:130976,rk:110386,sk:113746,tk:66557,vk:17310,wk:28631,xk:21589,yk:68012,zk:60480,Ak:138664,Bk:31571,Ck:76980,Dk:41577,Ek:45469,Fk:38669,Gk:13768,Hk:13777,Ik:62985,Jk:4724,Kk:59369,Lk:43927,Mk:43928,Nk:12924,Ok:100355,Rk:56219,Sk:27669,Tk:10337,Qk:47896,Uk:122629,Vk:121258,Wk:107598,Xk:127991,Yk:96639,Zk:107536,al:130169,bl:96661,dl:96658,fl:116646,
il:121122,jl:96660,kl:127738,ll:127083,ml:104443,nl:96659,ol:106442,pl:134840,ql:63667,rl:63668,sl:63669,ul:130686,vl:78314,wl:55761,xl:127098,yl:134841,zl:96368,Al:67374,Bl:48992,Cl:49956,Dl:31961,El:26388,Fl:23811,Gl:5E4,Hl:126250,Il:96370,Jl:47355,Kl:47356,Ll:37935,Ml:45521,Nl:21760,Ol:83769,Pl:49977,Ql:49974,Rl:93497,Sl:93498,Tl:34325,Ul:115803,Vl:123707,Wl:100081,Xl:35309,Yl:68314,Zl:25602,am:100339,bm:59018,cm:18248,dm:50625,em:9729,fm:37168,gm:37169,hm:21667,im:16749,jm:18635,km:39305,lm:18046,
mm:53969,nm:8213,om:93926,pm:102852,qm:110099,rm:22678,sm:69076,tm:137575,vm:139224,wm:100856,xm:17736,ym:3832,zm:55759,Am:64031,Bm:93044,Cm:93045,Dm:34388,Em:17657,Fm:17655,Gm:39579,Hm:39578,Im:77448,Jm:8196,Km:11357,Lm:69877,Mm:8197,Nm:82039};function bm(){var a=ob(cm),b;return Mf(new Ef(function(c,d){a.onSuccess=function(e){wh(e)?c(new dm(e)):d(new em("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new em("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new em("Request timed out","net.timeout",e))};
b=Ch("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Nf&&b.abort();
return Kf(c)})}
function em(a,b,c){Xa.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(em,Xa);function dm(a){this.xhr=a}
;function fm(){this.i=0;this.h=null}
fm.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.h),Df(a)?a:gm(a)):2===this.i&&b?(a=b.call(c,this.h),Df(a)?a:hm(a)):this};
fm.prototype.getValue=function(){return this.h};
fm.prototype.$goog_Thenable=!0;function hm(a){var b=new fm;a=void 0===a?null:a;b.i=2;b.h=void 0===a?null:a;return b}
function gm(a){var b=new fm;a=void 0===a?null:a;b.i=1;b.h=void 0===a?null:a;return b}
;function im(){if(Vd())return!0;var a=F("INNERTUBE_CLIENT_NAME");return!a||"WEB"!==a&&"MWEB"!==a||Kh&&Lh("applewebkit")&&!Lh("version")&&(!Lh("safari")||Lh("gsa/"))||uc&&Lh("version/")?!0:(a=Td.get("CONSENT",void 0))?a.startsWith("YES+"):!0}
;function jm(a){Xa.call(this,a.message||a.description||a.name);this.isMissing=a instanceof km;this.isTimeout=a instanceof em&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Nf}
v(jm,Xa);jm.prototype.name="BiscottiError";function km(){Xa.call(this,"Biscotti ID is missing from server")}
v(km,Xa);km.prototype.name="BiscottiMissingError";var cm={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},lm=null;function gh(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return Kf(Error("Biscotti id fetching has been disabled entirely."));if(!im())return Kf(Error("User has not consented - not fetching biscotti id."));if("1"==mb())return Kf(Error("Biscotti ID is not available in private embed mode"));lm||(lm=Mf(bm().then(mm),function(a){return nm(2,a)}));
return lm}
function mm(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new km;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new km;a=a.id;hh(a);lm=gm(a);om(18E5,2);return a}
function nm(a,b){b=new jm(b);hh("");lm=hm(b);0<a&&om(12E4,a-1);throw b;}
function om(a,b){Sg(function(){Mf(bm().then(mm,function(c){return nm(b,c)}),Ia)},a)}
function pm(){try{var a=C("yt.ads.biscotti.getId_");return a?a():gh()}catch(b){return Kf(b)}}
;function qm(a){if("1"!=mb()){a&&fh();try{pm().then(function(){},function(){}),Sg(qm,18E5)}catch(b){zg(b)}}}
;var rm=Date.now().toString();
function sm(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(rm)for(a=1,b=0;b<rm.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^rm.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var tm,um=y.ytLoggingDocDocumentNonce_;um||(um=sm(),Va("ytLoggingDocDocumentNonce_",um));tm=um;var vm={xf:0,Oc:1,Wc:2,Ii:3,zf:4,um:5,xj:6,Pk:7,uk:8,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS"};function wm(a){this.h=a}
function xm(a){return new wm({trackingParams:a})}
wm.prototype.getAsJson=function(){var a={};void 0!==this.h.trackingParams?a.trackingParams=this.h.trackingParams:(a.veType=this.h.veType,void 0!==this.h.veCounter&&(a.veCounter=this.h.veCounter),void 0!==this.h.elementIndex&&(a.elementIndex=this.h.elementIndex));void 0!==this.h.dataElement&&(a.dataElement=this.h.dataElement.getAsJson());void 0!==this.h.youtubeData&&(a.youtubeData=this.h.youtubeData);return a};
wm.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
wm.prototype.isClientVe=function(){return!this.h.trackingParams&&!!this.h.veType};function ym(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function zm(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Am(a){return F(zm(void 0===a?0:a),void 0)}
B("yt_logging_screen.getRootVeType",Am,void 0);function Bm(a){return(a=Am(void 0===a?0:a))?new wm({veType:a,youtubeData:void 0}):null}
function Cm(){var a=F("csn-to-ctt-auth-info");a||(a={},L("csn-to-ctt-auth-info",a));return a}
function Dm(a){a=void 0===a?0:a;var b=F(ym(a));if(!b&&!F("USE_CSN_FALLBACK",!0))return null;b||!M("use_undefined_csn_any_layer")&&0!=a||(b="UNDEFINED_CSN");return b?b:null}
B("yt_logging_screen.getCurrentCsn",Dm,void 0);function Em(a,b,c){var d=Cm();(c=Dm(c))&&delete d[c];b&&(d[a]=b)}
function Fm(a){return Cm()[a]}
B("yt_logging_screen.getCttAuthInfo",Fm,void 0);function Gm(a,b,c,d){c=void 0===c?0:c;if(a!==F(ym(c))||b!==F(zm(c)))Em(a,d,c),L(ym(c),a),L(zm(c),b),b=function(){setTimeout(function(){a&&xi("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:tm,clientScreenNonce:a},Fl)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
B("yt_logging_screen.setCurrentScreen",Gm,void 0);function Hm(a){sk.call(this,1,arguments);this.csn=a}
v(Hm,sk);var Bk=new tk("screen-created",Hm),Im=[],Km=Jm,Lm=0;function Mm(a,b,c,d){var e=d.filter(function(f){f.csn!==b?(f.csn=b,f=!0):f=!1;return f});
c={csn:b,parentVe:c.getAsJson(),childVes:bb(e,function(f){return f.getAsJson()})};
d=u(d);for(e=d.next();!e.done;e=d.next())e=e.value.getAsJson(),(kb(e)||!e.trackingParams&&!e.veType)&&Yl(Error("Child VE logged with no data"));d={cttAuthInfo:Fm(b),fa:b};"UNDEFINED_CSN"==b?Nm("visualElementAttached",c,d):a?xi("visualElementAttached",c,a,d):V("visualElementAttached",c,d)}
function Jm(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return Kc(b,3)}
function Nm(a,b,c){Im.push({payloadName:a,payload:b,options:c});Lm||(Lm=Ck())}
function Dk(a){if(Im){for(var b=u(Im),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,xi(c.payloadName,c.payload,null,c.options));Im.length=0}Lm=0}
;function Om(){this.i=new Set;this.h=new Set;this.j=new Map}
Om.prototype.clear=function(){this.i.clear();this.h.clear();this.j.clear()};
Ja(Om);function Pm(a){var b=Da.apply(1,arguments);if(!Qm(a)||b.some(function(e){return!Qm(e)}))throw Error("Only objects may be merged.");
var c=a;b=u(b);for(var d=b.next();!d.done;d=b.next())Rm(c,d.value);return c}
function Rm(a,b){for(var c in b)if(Qm(b[c])){if(c in a&&!Qm(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});Rm(a[c],b[c])}else if(Sm(b[c])){if(c in a&&!Sm(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);Tm(a[c],b[c])}else a[c]=b[c];return a}
function Tm(a,b){b=u(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Qm(c)?a.push(Rm({},c)):Sm(c)?a.push(Tm([],c)):a.push(c);return a}
function Qm(a){return"object"===typeof a&&!Array.isArray(a)}
function Sm(a){return"object"===typeof a&&Array.isArray(a)}
;function Um(a,b){sk.call(this,1,arguments)}
v(Um,sk);function Vm(a,b){sk.call(this,1,arguments)}
v(Vm,sk);var Wm=new tk("aft-recorded",Um),Xm=new tk("timing-sent",Vm);var Ym=window;function Zm(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var W=Ym.performance||Ym.mozPerformance||Ym.msPerformance||Ym.webkitPerformance||new Zm;var $m=!1,an={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Ta(W.clearResourceTimings||W.webkitClearResourceTimings||W.mozClearResourceTimings||W.msClearResourceTimings||W.oClearResourceTimings||Ia,W);function bn(a){var b=cn(a);if(b.aft)return b.aft;a=F((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function dn(){var a;if(M("csi_use_performance_navigation_timing")){var b,c,d,e=null===(d=null===(c=null===(b=null===(a=null===W||void 0===W?void 0:W.getEntriesByType)||void 0===a?void 0:a.call(W,"navigation"))||void 0===b?void 0:b[0])||void 0===c?void 0:c.toJSON)||void 0===d?void 0:d.call(c);e?(e.requestStart=en(e.requestStart),e.responseEnd=en(e.responseEnd),e.redirectStart=en(e.redirectStart),e.redirectEnd=en(e.redirectEnd),e.domainLookupEnd=en(e.domainLookupEnd),e.connectStart=en(e.connectStart),
e.connectEnd=en(e.connectEnd),e.responseStart=en(e.responseStart),e.secureConnectionStart=en(e.secureConnectionStart),e.domainLookupStart=en(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=W.timing}else a=W.timing;return a}
function fn(){return M("csi_use_time_origin")&&W.timeOrigin?Math.floor(W.timeOrigin):W.timing.navigationStart}
function en(a){return Math.round(fn()+a)}
function gn(a){var b;(b=C("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Va("ytcsi."+(a||"")+"data_",b));return b}
function hn(a){a=gn(a);a.info||(a.info={});return a.info}
function cn(a){a=gn(a);a.tick||(a.tick={});return a.tick}
function jn(a){var b=gn(a).nonce;b||(b=sm(),gn(a).nonce=b);return b}
function kn(a){var b=cn(a||""),c=bn(a);c&&!$m&&(yk(Wm,new Um(Math.round(c-b._start),a)),$m=!0)}
;function ln(){if(W.getEntriesByType){var a=W.getEntriesByType("paint");if(a=db(a,function(b){return"first-paint"===b.name}))return en(a.startTime)}a=W.timing;
return a.Lb?Math.max(0,a.Lb):0}
;function mn(){var a=C("ytcsi.debug");a||(a=[],B("ytcsi.debug",a,void 0),B("ytcsi.reference",{},void 0));return a}
function nn(a){a=a||"";var b=C("ytcsi.reference");b||(mn(),b=C("ytcsi.reference"));if(b[a])return b[a];var c=mn(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var pn=y.ytLoggingLatencyUsageStats_||{};B("ytLoggingLatencyUsageStats_",pn,void 0);function qn(){this.h=0}
function rn(){qn.h||(qn.h=new qn);return qn.h}
qn.prototype.tick=function(a,b,c,d){sn(this,"tick_"+a+"_"+b)||V("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c,cttAuthInfo:d})};
qn.prototype.info=function(a,b,c){var d=Object.keys(a).join("");sn(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,V("latencyActionInfo",a,{cttAuthInfo:c}))};
qn.prototype.span=function(a,b,c){var d=Object.keys(a).join("");sn(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,V("latencyActionSpan",a,{cttAuthInfo:c}))};
function sn(a,b){pn[b]=pn[b]||{count:0};var c=pn[b];c.count++;c.time=N();a.h||(a.h=Wg(function(){var d=N(),e;for(e in pn)pn[e]&&6E4<d-pn[e].time&&delete pn[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new Xi("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Yl(c)),!0):!1}
;var X={},tn=(X.auto_search="LATENCY_ACTION_AUTO_SEARCH",X.ad_to_ad="LATENCY_ACTION_AD_TO_AD",X.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",X["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",X.app_startup="LATENCY_ACTION_APP_STARTUP",X["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",X["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",X["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",X.browse="LATENCY_ACTION_BROWSE",X.channels="LATENCY_ACTION_CHANNELS",X.creator_channel_dashboard=
"LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",X["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",X["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",X["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",X["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",X["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",X["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",X["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",X["channel.playlists"]=
"LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",X["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",X["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",X["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",X.chips="LATENCY_ACTION_CHIPS",X["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",X["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",X.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",X.embed="LATENCY_ACTION_EMBED",X.entity_key_serialization_perf=
"LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",X.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",X.explore="LATENCY_ACTION_EXPLORE",X.home="LATENCY_ACTION_HOME",X.library="LATENCY_ACTION_LIBRARY",X.live="LATENCY_ACTION_LIVE",X.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",X.onboarding="LATENCY_ACTION_ONBOARDING",X.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",X.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",X.parent_tools_dashboard=
"LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",X.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",X["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",X["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",X.prebuffer="LATENCY_ACTION_PREBUFFER",X.prefetch="LATENCY_ACTION_PREFETCH",X.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",X.profile_switcher="LATENCY_ACTION_LOGIN",X.reel_watch="LATENCY_ACTION_REEL_WATCH",X.results="LATENCY_ACTION_RESULTS",X.search_ui="LATENCY_ACTION_SEARCH_UI",X.search_suggest=
"LATENCY_ACTION_SUGGEST",X.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",X.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",X.seek="LATENCY_ACTION_PLAYER_SEEK",X.settings="LATENCY_ACTION_SETTINGS",X.tenx="LATENCY_ACTION_TENX",X.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",X.watch="LATENCY_ACTION_WATCH",X.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",X["watch,watch7"]="LATENCY_ACTION_WATCH",X["watch,watch7_html5"]="LATENCY_ACTION_WATCH",X["watch,watch7ad"]="LATENCY_ACTION_WATCH",X["watch,watch7ad_html5"]=
"LATENCY_ACTION_WATCH",X.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",X.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",X["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",X["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",X["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",X["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",X["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",X["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",X["video.live_streaming"]=
"LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",X["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",X["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",X.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",X.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",X.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",X),Y={},un=(Y.ad_allowed="adTypesAllowed",Y.yt_abt="adBreakType",Y.ad_cpn="adClientPlaybackNonce",Y.ad_docid="adVideoId",Y.yt_ad_an=
"adNetworks",Y.ad_at="adType",Y.aida="appInstallDataAgeMs",Y.browse_id="browseId",Y.p="httpProtocol",Y.t="transportProtocol",Y.cs="commandSource",Y.cpn="clientPlaybackNonce",Y.ccs="creatorInfo.creatorCanaryState",Y.ctop="creatorInfo.topEntityType",Y.csn="clientScreenNonce",Y.docid="videoId",Y.GetHome_rid="requestIds",Y.GetSearch_rid="requestIds",Y.GetPlayer_rid="requestIds",Y.GetWatchNext_rid="requestIds",Y.GetBrowse_rid="requestIds",Y.GetLibrary_rid="requestIds",Y.is_continuation="isContinuation",
Y.is_nav="isNavigation",Y.b_p="kabukiInfo.browseParams",Y.is_prefetch="kabukiInfo.isPrefetch",Y.is_secondary_nav="kabukiInfo.isSecondaryNav",Y.nav_type="kabukiInfo.navigationType",Y.prev_browse_id="kabukiInfo.prevBrowseId",Y.query_source="kabukiInfo.querySource",Y.voz_type="kabukiInfo.vozType",Y.yt_lt="loadType",Y.mver="creatorInfo.measurementVersion",Y.yt_ad="isMonetized",Y.nr="webInfo.navigationReason",Y.nrsu="navigationRequestedSameUrl",Y.ncnp="webInfo.nonPreloadedNodeCount",Y.pnt="performanceNavigationTiming",
Y.prt="playbackRequiresTap",Y.plt="playerInfo.playbackType",Y.pis="playerInfo.playerInitializedState",Y.paused="playerInfo.isPausedOnLoad",Y.yt_pt="playerType",Y.fmt="playerInfo.itag",Y.yt_pl="watchInfo.isPlaylist",Y.yt_pre="playerInfo.preloadType",Y.yt_ad_pr="prerollAllowed",Y.pa="previousAction",Y.yt_red="isRedSubscriber",Y.rce="mwebInfo.responseContentEncoding",Y.rc="resourceInfo.resourceCache",Y.scrh="screenHeight",Y.scrw="screenWidth",Y.st="serverTimeMs",Y.ssdm="shellStartupDurationMs",Y.br_trs=
"tvInfo.bedrockTriggerState",Y.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Y.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Y.label="tvInfo.label",Y.is_mdx="tvInfo.isMdx",Y.preloaded="tvInfo.isPreloaded",Y.aac_type="tvInfo.authAccessCredentialType",Y.upg_player_vis="playerInfo.visibilityState",Y.query="unpluggedInfo.query",Y.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Y.yt_vst="videoStreamType",Y.vph="viewportHeight",Y.vpw="viewportWidth",Y.yt_vis="isVisible",Y.rcl="mwebInfo.responseContentLength",
Y.GetSettings_rid="requestIds",Y.GetTrending_rid="requestIds",Y.GetMusicSearchSuggestions_rid="requestIds",Y.REQUEST_ID="requestIds",Y),vn="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),wn={},xn=(wn.ccs="CANARY_STATE_",
wn.mver="MEASUREMENT_VERSION_",wn.pis="PLAYER_INITIALIZED_STATE_",wn.yt_pt="LATENCY_PLAYER_",wn.pa="LATENCY_ACTION_",wn.ctop="TOP_ENTITY_TYPE_",wn.yt_vst="VIDEO_STREAM_TYPE_",wn),yn="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function zn(a){return!!F("FORCE_CSI_ON_GEL",!1)||M("csi_on_gel")||M("enable_csi_on_gel")||M("unplugged_tvhtml5_csi_on_gel")||!!gn(a).useGel}
function An(a,b,c){var d=Bn(c);d.gelTicks&&(d.gelTicks["tick_"+a]=!0);c||b||N();if(zn(c)){nn(c||"").tick[a]=b||N();d=jn(c);var e=gn(c).cttAuthInfo;"_start"===a?(a=rn(),sn(a,"baseline_"+d)||V("latencyActionBaselined",{clientActionNonce:d},{timestamp:b,cttAuthInfo:e})):rn().tick(a,d,b,e);kn(c);return!0}return!1}
function Cn(a,b,c){c=Bn(c);if(c.gelInfos)c.gelInfos["info_"+a]=!0;else{var d={};c.gelInfos=(d["info_"+a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in un){c=un[a];0<=$a(vn,c)&&(b=!!b);a in xn&&"string"===typeof b&&(b=xn[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Pm({},d)}0<=$a(yn,a)||Yl(new Xi("Unknown label logged with GEL CSI",a))}
function Bn(a){a=gn(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Dn(a){a=Bn(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
;function En(a,b,c){null!==b&&(hn(c)[a]=b,zn(c)?(a=Cn(a,b,c))&&zn(c)&&(b=nn(c||""),Pm(b.info,a),Pm(Dn(c),a),b=jn(c),c=gn(c).cttAuthInfo,rn().info(a,b,c)):nn(c||"").info[a]=b)}
function Z(a,b,c){var d=cn(c);if(!b&&"_"!==a[0]){var e=a;W.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),W.mark(e))}e=b||N();d[a]=e;An(a,b,c)||c||(Fn(),nn("").tick[a]=b||N());return d[a]}
function Gn(){var a=jn(void 0);requestAnimationFrame(function(){setTimeout(function(){a===jn(void 0)&&Z("ol",void 0,void 0)},0)})}
function Fn(){if(!C("yt.timing.pingSent_")){var a=F("TIMING_ACTION",void 0),b=cn();if(a=!!C("ytglobal.timingready_")&&a)a="_start"in cn(void 0);if(a&&bn()){kn();a=!0;var c=F("TIMING_WAIT",[]);if(c.length)for(var d=0,e=c.length;d<e;++d)if(!(c[d]in b)){a=!1;break}if(a&&!zn()){c=cn();d=hn();e=c._start;var f=F("CSI_SERVICE_NAME","youtube");a={v:2,s:f,action:F("TIMING_ACTION",void 0)};b=d.srt;void 0!==c.srt&&delete d.srt;c.aft=bn();var g=cn(void 0),h=g.pbr,k=g.vc;g=g.pbs;h&&k&&g&&h<k&&k<g&&hn(void 0).yt_pvis&&
"youtube"===f&&(En("yt_lt","hot_bg"),f=c.vc,h=c.pbs,delete c.aft,d.aft=Math.round(h-f));for(var l in d)"_"!==l.charAt(0)&&(a[l]=d[l]);c.ps=N();l={};f=[];for(var n in c)"_"!==n.charAt(0)&&(h=Math.round(c[n]-e),l[n]=h,f.push(n+"."+h));a.rt=f.join(",");n=!!d.ap;c="";for(var p in a)a.hasOwnProperty(p)&&(c+="&"+p+"="+a[p]);p="/csi_204?"+c.substring(1);window.navigator&&n?Rh(p):Oh(p);B("yt.timing.pingSent_",!0,void 0);yk(Xm,new Vm(l.aft+(Number(b)||0)))}}}}
function Hn(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=Ig+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function In(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);cc()&&a.setAttribute("nonce",cc());return c?(a=W.getEntriesByName(c))&&a[0]&&(a=a[0],c=fn(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function Jn(){var a=window.location.protocol,b=W.getEntriesByType("resource");b=ab(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=cb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",en(b.startTime)),Z("wffe",en(b.responseEnd)))}
var Kn=window;Kn.ytcsi&&(Kn.ytcsi.info=En,Kn.ytcsi.tick=Z);function Ln(){this.u=[];this.o=[];this.h=[];this.l=[];this.m=[];this.i=new Set;this.B=new Map}
function Mn(a,b,c){c=void 0===c?0:c;b.then(function(d){var e,f;a.i.has(c)&&a.j&&a.j();var g=Dm(c),h=Bm(c);g&&h&&((null===(e=null===d||void 0===d?void 0:d.response)||void 0===e?0:e.trackingParams)&&Mm(a.client,g,h,[xm(d.response.trackingParams)]),(null===(f=null===d||void 0===d?void 0:d.playerResponse)||void 0===f?0:f.trackingParams)&&Mm(a.client,g,h,[xm(d.playerResponse.trackingParams)]))})}
function Nn(a,b,c,d){d=void 0===d?0:d;if(a.i.has(d))a.u.push([b,c]);else{var e=Dm(d);c=c||Bm(d);e&&c&&Mm(a.client,e,c,[b])}}
Ln.prototype.clickCommand=function(a,b,c){a=a.clickTrackingParams;c=void 0===c?0:c;if(a)if(c=Dm(void 0===c?0:c)){var d=this.client;var e="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";a={csn:c,ve:xm(a).getAsJson(),gestureType:e};b&&(a.clientData=b);b={cttAuthInfo:Fm(c),fa:c};"UNDEFINED_CSN"==c?Nm("visualElementGestured",a,b):d?xi("visualElementGestured",a,d,b):V("visualElementGestured",a,b);b=!0}else b=!1;else b=!1;return b};
function On(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){Pn(a,b,c);var f=Bm(c.layer);if(f){for(var g=u(a.u),h=g.next();!h.done;h=g.next())h=h.value,Nn(a,h[0],h[1]||f,c.layer);f=u(a.o);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=Dm(g);var l=k[0]||Bm(g);h&&l&&(g=a.client,k=k[1],k={csn:h,ve:l.getAsJson(),clientData:k},l={cttAuthInfo:Fm(h),fa:h},"UNDEFINED_CSN"==h?Nm("visualElementStateChanged",k,l):g?xi("visualElementStateChanged",k,g,l):V("visualElementStateChanged",
k,l))}}};
Dm(c.layer)||a.j();if(c.fb)for(var d=u(c.fb),e=d.next();!e.done;e=d.next())Mn(a,e.value,c.layer);else Zl(Error("Delayed screen needs a data promise."))}
function Pn(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Mb?c.Mb:c.layer;var e=Dm(d);d=Bm(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=F("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=a.client;h=f;var l=c.eb,n=c.cttAuthInfo,p=c.Tm,t=Km(),q={csn:t,pageVe:(new wm({veType:b,youtubeData:g})).getAsJson()};h&&h.visualElement?(q.implicitGesture=
{parentCsn:h.clientScreenNonce,gesturedVe:h.visualElement.getAsJson()},p&&(q.implicitGesture.gestureType=p)):h&&Yl(new Xi("newScreen() parent element does not have a VE - rootVe",b));l&&(q.cloneCsn=l);l={cttAuthInfo:n,fa:t};k?xi("screenCreated",q,k,l):V("screenCreated",q,l);yk(Bk,new Hm(t));var z=t}catch(A){$l(A,{an:b,rootVe:d,parentVisualElement:void 0,Sm:e,Zm:f,eb:c.eb});Zl(A);return}Gm(z,b,c.layer,c.cttAuthInfo);if((b=e&&"UNDEFINED_CSN"!==e&&d)&&!(b=M("screen_manager_skip_hide_killswitch"))){a:{b=
u(Object.values(vm));for(f=b.next();!f.done;f=b.next())if(Dm(f.value)==e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,f=!0,k=(f=void 0===f?!1:f)?16:8,d={csn:e,ve:d.getAsJson(),eventType:k},f={cttAuthInfo:Fm(e),fa:e,Bb:f},"UNDEFINED_CSN"==e?Nm("visualElementHidden",d,f):b?xi("visualElementHidden",d,b,f):V("visualElementHidden",d,f));a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=z||"");En("csn",z);Om.getInstance().clear();d=Bm(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||
M("music_web_mark_root_visible"))&&(e=z,z={csn:e,ve:d.getAsJson(),eventType:1},b={cttAuthInfo:Fm(e),fa:e},"UNDEFINED_CSN"==e?Nm("visualElementShown",z,b):V("visualElementShown",z,b));a.i.delete(c.layer||0);a.j=void 0;e=u(a.B);for(z=e.next();!z.done;z=e.next())b=u(z.value),z=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Nn(a,z,d,c.layer);for(c=0;c<a.l.length;c++){e=a.l[c];try{e()}catch(A){Zl(A)}}for(c=a.l.length=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(A){Zl(A)}}}
;function Qn(a){a&&(a.dataset?a.dataset[Rn("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Sn(a,b){return a?a.dataset?a.dataset[Rn(b)]:a.getAttribute("data-"+b):null}
var Tn={};function Rn(a){return Tn[a]||(Tn[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Un=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Vn=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Wn(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Un,""),c=c.replace(Vn,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Xn(a,b,c)}
function Xn(a,b,c){c=void 0===c?null:c;var d=Yn(a),e=document.getElementById(d),f=e&&Sn(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Wh(d,b),b=""+Oa(b),Zn[b]=f),g||(e=$n(a,d,function(){Sn(e,"loaded")||(Qn(e),Zh(d),Sg(Ua($h,d),0))},c)))}
function $n(a,b,c,d){d=void 0===d?null:d;var e=Bd(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);ud(e,vf(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function ao(a){a=Yn(a);var b=document.getElementById(a);b&&($h(a),b.parentNode.removeChild(b))}
function bo(a,b){a&&b&&(a=""+Oa(b),(a=Zn[a])&&Yh(a))}
function Yn(a){var b=document.createElement("a");$b(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+ec(a)}
var Zn={};var co=[],eo=!1;function fo(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&im()&&"1"!=mb()){var a=function(){eo=!0;"google_ad_status"in window?L("DCLKSTAT",1):L("DCLKSTAT",2)};
try{Wn("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}co.push($g.L(function(){if(!(eo||"google_ad_status"in window)){try{bo("//static.doubleclick.net/instream/ad_status.js",a)}catch(b){}eo=!0;L("DCLKSTAT",3)}},5E3))}}
function go(){var a=Number(F("DCLKSTAT",0));return isNaN(a)?0:a}
;function ho(){this.i=!1;this.h=null}
ho.prototype.initialize=function(a,b,c,d){d=void 0===d?!1:d;var e,f;if(a.program){var g=null!==(e=a.interpreterScript)&&void 0!==e?e:null,h=null!==(f=a.interpreterUrl)&&void 0!==f?f:null;if(a.interpreterSafeScript){g=a.interpreterSafeScript;wb("From proto message. b/166824318");g=g.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var k=tb();g=k?k.createScript(g):g;g=(new yb(g)).toString()}a.interpreterSafeUrl&&(h=a.interpreterSafeUrl,wb("From proto message. b/166824318"),h=Cb(h.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||
"").toString());io(this,g,h,a.program,b,c,d)}else Yl(Error("Cannot initialize botguard without program"))};
function io(a,b,c,d,e,f,g){g=void 0===g?!1:g;c?(a.i=!0,Wn(c,function(){a.i=!1;var h=0<=c.indexOf("/th/");(h?window.trayride:window.botguard)?jo(a,d,!!g,h,e):(ao(c),Yl(new Xi("Unable to load Botguard","from "+c)))},f)):b&&(f=Bd(document,"SCRIPT"),f.textContent=b,f.nonce=cc(),document.head.appendChild(f),document.head.removeChild(f),((b=b.includes("trayride"))?window.trayride:window.botguard)?jo(a,d,!!g,b,e):Yl(Error("Unable to load Botguard from JS")))}
function jo(a,b,c,d,e){var f,g;if(d=d?null===(f=window.trayride)||void 0===f?void 0:f.ad:null===(g=window.botguard)||void 0===g?void 0:g.bg)if(c)try{ko(a,new d(b,e?function(){return e(b)}:Ia))}catch(h){h instanceof Error&&Yl(h)}else{try{ko(a,new d(b))}catch(h){h instanceof Error&&Yl(h)}e&&e(b)}else Yl(Error("Failed to finish initializing VM"))}
ho.prototype.invoke=function(a){a=void 0===a?{}:a;return this.h?this.h.hasOwnProperty("hot")?this.h.hot(void 0,void 0,a):this.h.invoke(void 0,void 0,a):null};
ho.prototype.dispose=function(){this.h=null};
function ko(a,b){a.h=b}
;var lo=new ho;function mo(){return!!lo.h}
function no(a){a=void 0===a?{}:a;return lo.invoke(a)}
;var oo=window,po=/[A-Za-z]+\/[0-9.]+/g;function qo(a,b){if(a.replace(po,"")!==b.replace(po,""))return!1;a=a.match(po);b=b.match(po);if(a.length!==b.length)return!1;for(var c=0;c<a.length;c++){var d=a[c],e=b[c];if(!d.startsWith(e)&&!e.startsWith(d))return!1}return!0}
function ro(){var a=oo.uaChPolyfill.state;if(0===a.type)V("clientHintsPolyfillEvent",{clientHintsSupported:!1});else{var b=navigator.userAgent,c=void 0!==a.syntheticUa&&qo(a.syntheticUa,b),d={clientHintsSupported:!0,uaAccessedBeforePolyfill:a.didAccessUaBeforePolyfillAvailable,syntheticUaMatches:c};a.didAccessUaBeforePolyfillAvailable&&(d.uaAccessBeforePolyfillCount=a.uaAccessBeforePolyfillCount,a.firstAccessUaError&&(d.firstUaAccessStack=String(a.firstAccessUaError.stack).replace(/\n/g,""),Zl(a.firstAccessUaError)),
d.polyfillAvailabilityDelayMs=a.polyfillAvailabilityDelay);V("clientHintsPolyfillEvent",d);c||(b={syntheticUa:a.syntheticUa,ua:b},b.brand=a.data.brands.map(function(e){return'"'+e.brand+'"; v="'+e.version+'"'}),b.mobileness=a.data.mobile,a=a.data.values,a.architecture&&(b.platformArchitecture=a.architecture),a.model&&(b.model=a.model),a.platform&&(b.platformBrand=a.platform),a.platformVersion&&(b.platformVersion=a.platformVersion),a.uaFullVersion&&(b.fullVersion=a.uaFullVersion),V("clientHintsPolyfillDiagnostics",
b))}}
var so=!1;function to(){var a;1===(null===(a=oo.uaChPolyfill)||void 0===a?void 0:a.state.type)?so||(oo.uaChPolyfill.onReady=to,so=!0):oo.uaChPolyfill&&ro()}
;function uo(a,b,c){I.call(this);var d=this;c=c||F("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.j=b||null;this.F="*";this.l=c;this.sessionId=null;this.channel="widget";this.H=!!a;this.B=function(e){a:if(!("*"!=d.l&&e.origin!=d.l||d.j&&e.source!=d.j||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.H&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.l=d.F=e.origin);d.j=e.source;d.sessionId=f.id;d.i&&(d.i(),d.i=null);break;case "command":d.m&&(!d.o||0<=$a(d.o,f.func))&&d.m(f.func,f.args,e.origin)}}};
this.o=this.i=this.m=null;window.addEventListener("message",this.B)}
v(uo,I);uo.prototype.sendMessage=function(a,b){if(b=b||this.j){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.F)}catch(d){Ag(d)}}};
uo.prototype.G=function(){window.removeEventListener("message",this.B);I.prototype.G.call(this)};function vo(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new uo(!!F("WIDGET_ID_ENFORCE")),b=this.Ob.bind(this);a.m=b;a.o=null;this.h.channel="widget";if(a=F("WIDGET_ID"))this.h.sessionId=a}
m=vo.prototype;m.Ob=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.j[a]||"onReady"===a||(this.addEventListener(a,wo(this,a)),this.j[a]=!0)):this.Ya(a,b,c)};
m.Ya=function(){};
function wo(a,b){return function(c){return a.sendMessage(b,c)}}
m.addEventListener=function(){};
m.Cb=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Na());this.sendMessage("onReady");E(this.i,this.rb,this);this.i=[]};
m.Na=function(){return null};
function xo(a,b){a.sendMessage("infoDelivery",b)}
m.rb=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
m.sendMessage=function(a,b){this.rb({event:a,info:void 0===b?null:b})};
m.dispose=function(){this.h=null};function yo(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function zo(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Ao(a,b,c,d){if(Na(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Bo(a){vo.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.Vb.bind(this));this.addEventListener("onVolumeChange",this.Wb.bind(this));this.addEventListener("onApiChange",this.Qb.bind(this));this.addEventListener("onPlaybackQualityChange",this.Sb.bind(this));this.addEventListener("onPlaybackRateChange",this.Tb.bind(this));this.addEventListener("onStateChange",this.Ub.bind(this));this.addEventListener("onWebglSettingsChanged",
this.Xb.bind(this))}
v(Bo,vo);m=Bo.prototype;
m.Ya=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&yo(a)){var d=b;if(Na(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=zo(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=zo(e);break;case "loadPlaylist":case "cuePlaylist":e=Ao(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);yo(a)&&xo(this,this.Na())}};
m.onReady=function(){var a=this.Cb.bind(this);this.h.i=a};
m.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
m.Na=function(){if(!this.api)return null;var a=this.api.getApiInterface();eb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
m.Ub=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());xo(this,a)};
m.Sb=function(a){xo(this,{playbackQuality:a})};
m.Tb=function(a){xo(this,{playbackRate:a})};
m.Qb=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.api.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
m.Wb=function(){xo(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
m.Vb=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());xo(this,a)};
m.Xb=function(){var a={sphericalProperties:this.api.getSphericalProperties()};xo(this,a)};
m.dispose=function(){vo.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Co(a){I.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.nb,this)}
v(Co,I);m=Co.prototype;m.start=function(){this.started||this.h||(this.started=!0,this.connection.ia("RECEIVING"))};
m.ia=function(a,b){this.started&&!this.h&&this.connection.ia(a,b)};
m.nb=function(a,b,c){if(this.started&&!this.h){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Do(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Eo(a,c))&&this.ia(a,c))}}};
m.addListener=function(a){if(!(a in this.i)){var b=this.Rb.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
m.Rb=function(a,b){this.started&&!this.h&&this.connection.ia(a,this.Ma(a,b))};
m.Ma=function(a,b){if(null!=b)return{value:b}};
m.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
m.G=function(){var a=this.connection;a.h||Xf(a.i,"command",this.nb,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);I.prototype.G.call(this)};function Fo(a,b){Co.call(this,b);this.api=a;this.start()}
v(Fo,Co);Fo.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
Fo.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Do(a,b){switch(a){case "loadVideoById":return a=zo(b),[a];case "cueVideoById":return a=zo(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Ao(b),[a];case "cuePlaylist":return a=Ao(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Eo(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Fo.prototype.Ma=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Co.prototype.Ma.call(this,a,b)};
Fo.prototype.G=function(){Co.prototype.G.call(this);delete this.api};function Go(a){a=void 0===a?!1:a;I.call(this);this.i=new K(a);$d(this,Ua(Yd,this.i))}
D(Go,I);Go.prototype.subscribe=function(a,b,c){return this.h?0:this.i.subscribe(a,b,c)};
Go.prototype.l=function(a,b){this.h||this.i.ha.apply(this.i,arguments)};function Ho(a,b,c){Go.call(this);this.j=a;this.destination=b;this.id=c}
v(Ho,Go);Ho.prototype.ia=function(a,b){this.h||this.j.ia(this.destination,this.id,a,b)};
Ho.prototype.G=function(){this.destination=this.j=null;Go.prototype.G.call(this)};function Io(a,b,c){I.call(this);this.destination=a;this.origin=c;this.i=Pg(window,"message",this.j.bind(this));this.connection=new Ho(this,a,b);$d(this,Ua(Yd,this.connection))}
v(Io,I);Io.prototype.ia=function(a,b,c,d){this.h||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(xf(a),this.origin))};
Io.prototype.j=function(a){var b;if(b=!this.h)if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.h||c.l("command",b.command,b.data,a.origin))}};
Io.prototype.G=function(){Qg(this.i);this.destination=null;I.prototype.G.call(this)};function Jo(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||ob(b);this.assets=a.assets||{};this.attrs=a.attrs||ob(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Jo.prototype.clone=function(){var a=new Jo,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ka(c)?a[b]=ob(c):a[b]=c}return a};var Ko=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function Lo(a){a=a||"";if(window.spf){var b=a.match(Ko);spf.style.load(a,b?b[1]:"",void 0)}else Mo(a)}
function Mo(a){var b=No(a),c=document.getElementById(b),d=c&&Sn(c,"loaded");d||c&&!d||(c=Oo(a,b,function(){Sn(c,"loaded")||(Qn(c),Zh(b),Sg(Ua($h,b),0))}))}
function Oo(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=vf(a);ac(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function No(a){var b=Bd(document,"A");wb("This URL is never added to the DOM");$b(b,new Mb(a,Nb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+ec(a)}
;function Po(){I.call(this);this.i=[]}
v(Po,I);Po.prototype.G=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.ab,void 0)}I.prototype.G.call(this)};function Qo(){Po.apply(this,arguments)}
v(Qo,Po);function Ro(a,b,c,d){I.call(this);var e=this;this.H=b;this.webPlayerContextConfig=d;this.Ia=!1;this.api={};this.la=this.o=null;this.N=new K;this.i={};this.Y=this.va=this.elementId=this.Ja=this.config=null;this.R=!1;this.l=this.B=null;this.wa={};this.ub=["onReady"];this.lastError=null;this.Za=NaN;this.F={};this.vb=new Qo(this);this.ka=0;this.j=this.m=a;$d(this,Ua(Yd,this.N));So(this);To(this);$d(this,Ua(Yd,this.vb));c?this.ka=Sg(function(){e.loadNewVideoConfig(c)},0):d&&(Uo(this),Vo(this))}
v(Ro,I);m=Ro.prototype;m.getId=function(){return this.H};
m.loadNewVideoConfig=function(a){if(!this.h){this.ka&&(Tg(this.ka),this.ka=0);var b=a||{};b instanceof Jo||(b=new Jo(b));this.config=b;this.setConfig(a);Vo(this);this.isReady()&&Wo(this)}};
function Uo(a){var b,c;a.webPlayerContextConfig?c=a.webPlayerContextConfig.rootElementId:c=a.config.attrs.id;a.elementId=c||a.elementId;"video-player"===a.elementId&&(a.elementId=a.H,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.H:a.config.attrs.id=a.H);(null===(b=a.j)||void 0===b?void 0:b.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
m.setConfig=function(a){var b;this.Ja=a;this.config=Xo(a);Uo(this);this.va||(this.va=Yo(this,(null===(b=this.config.args)||void 0===b?void 0:b.jsapicallback)||"onYouTubePlayerReady"));this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null===(c=this.config)||void 0===c?0:c.attrs)a=this.config.attrs,(c=a.width)&&this.j&&(this.j.style.width=Kd(Number(c)||c)),(a=a.height)&&this.j&&(this.j.style.height=Kd(Number(a)||a))};
function Wo(a){var b;a.config&&!0!==a.config.loaded&&(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay?a.api.loadVideoByPlayerVars(null!==(b=a.config.args)&&void 0!==b?b:null):a.api.cueVideoByPlayerVars(a.config.args))}
function Zo(a){var b=!0,c=$o(a);c&&a.config&&(a=ap(a),b=Sn(c,"version")===a);return b&&!!C("yt.player.Application.create")}
function Vo(a){if(!a.h&&!a.R){var b=Zo(a);if(b&&"html5"===($o(a)?"html5":null))a.Y="html5",a.isReady()||bp(a);else if(cp(a),a.Y="html5",b&&a.l&&a.m)a.m.appendChild(a.l),bp(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.B=function(){c=!0;var d=dp(a,"player_bootstrap_method")?C("yt.player.Application.createAlternate")||C("yt.player.Application.create"):C("yt.player.Application.create");var e=a.config?Xo(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig);bp(a)};
a.R=!0;b?a.B():(Wn(ap(a),a.B),(b=ep(a))&&Lo(b),fp(a)&&!c&&B("yt.player.Application.create",null,void 0))}}}
function $o(a){var b=xd(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function bp(a){var b;if(!a.h){var c=$o(a),d=!1;c&&c.getApiInterface&&c.getApiInterface()&&(d=!0);d?(a.R=!1,!dp(a,"html5_remove_not_servable_check_killswitch")&&(null===c||void 0===c?0:c.isNotServable)&&a.config&&(null===c||void 0===c?0:c.isNotServable(null===(b=a.config.args)||void 0===b?void 0:b.video_id))||gp(a)):a.Za=Sg(function(){bp(a)},50)}}
function gp(a){So(a);a.Ia=!0;var b=$o(a);if(b){a.o=hp(a,b,"addEventListener");a.la=hp(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=hp(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.o&&a.o(g,a.i[g]);Wo(a);a.va&&a.va(a.api);a.N.ha("onReady",a.api)}
function hp(a,b,c){var d=b[c];return function(){var e=Da.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Yl(f))}}}
function So(a){a.Ia=!1;if(a.la)for(var b in a.i)a.i.hasOwnProperty(b)&&a.la(b,a.i[b]);for(var c in a.F)a.F.hasOwnProperty(c)&&Tg(Number(c));a.F={};a.o=null;a.la=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.Ja};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
m.isReady=function(){return this.Ia};
function To(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Zh("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Zh("WATCH_LATER_VIDEO_REMOVED",b)});
a.addEventListener("onAdAnnounce",function(b){Zh("a11y-announce",b)})}
m.addEventListener=function(a,b){var c=this,d=Yo(this,b);d&&(0<=$a(this.ub,a)||this.i[a]||(b=ip(this,a),this.o&&this.o(a,b)),this.N.subscribe(a,d),"onReady"===a&&this.isReady()&&Sg(function(){d(c.api)},0))};
m.removeEventListener=function(a,b){this.h||(b=Yo(this,b))&&Xf(this.N,a,b)};
function Yo(a,b){var c=b;if("string"===typeof b){if(a.wa[b])return a.wa[b];c=function(){var d=Da.apply(0,arguments),e=C(b);if(e)try{e.apply(y,d)}catch(f){Zl(f)}};
a.wa[b]=c}return c?c:null}
function ip(a,b){var c="ytPlayer"+b+a.H;a.i[b]=c;y[c]=function(d){var e=Sg(function(){if(!a.h){a.N.ha(b,d);var f=a.F,g=String(e);g in f&&delete f[g]}},0);
lb(a.F,String(e))};
return c}
m.getPlayerType=function(){return this.Y||($o(this)?"html5":null)};
m.getLastError=function(){return this.lastError};
function cp(a){a.cancel();So(a);a.Y=null;a.config&&(a.config.loaded=!1);var b=$o(a);b&&(Zo(a)||!fp(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
m.cancel=function(){this.B&&bo(ap(this),this.B);Tg(this.Za);this.R=!1};
m.G=function(){cp(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){Zl(b)}this.wa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.Ja=this.config=this.api=null;delete this.m;delete this.j;I.prototype.G.call(this)};
function fp(a){var b,c;a=null===(c=null===(b=a.config)||void 0===b?void 0:b.args)||void 0===c?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function ap(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function ep(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function dp(a,b){var c;if(a.webPlayerContextConfig)var d=a.webPlayerContextConfig.serializedExperimentFlags;else if(null===(c=a.config)||void 0===c?0:c.args)d=a.config.args.fflags;return"true"===kh(d||"","&")[b]}
function Xo(a){for(var b={},c=u(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?ob(e):e}return b}
;var jp={},kp="player_uid_"+(1E9*Math.random()>>>0);function lp(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?xd(d):d;var e=kp+"_"+Oa(d),f=jp[e];if(f&&c)return mp(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new Ro(d,e,a,b);jp[e]=f;Zh("player-added",f.api);$d(f,function(){delete jp[f.getId()]});
return f.api}
function mp(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var np=null,op=null,pp=null;function qp(){var a=np.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function rp(a,b,c){a="ST-"+ec(a).toString(36);b=b?jc(b):"";c=c||5;im()&&zi(a,b,c)}
;function sp(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=F("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=F("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=hc(window.location.href);g&&f.push(g);g=hc(d);if(0<=$a(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),$b(f,d),d=f.href),d){g=d.match(fc);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:Dm()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&rp(d,b,k)}else rp(d,b)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var n=void 0===n?"":n;var p=void 0===p?window:p;c=p.location;a=kc(a,l)+n;var t=void 0===t?sd:t;a:{t=void 0===t?sd:t;for(l=0;l<t.length;++l)if(n=t[l],n instanceof qd&&n.isValid(a)){t=new od(a,md);break a}t=void 0}c.href=td(t||pd)}return!0}
;B("yt.setConfig",L,void 0);B("yt.config.set",L,void 0);B("yt.setMsg",Cg,void 0);B("yt.msgs.set",Cg,void 0);B("yt.logging.errors.log",Zl,void 0);
B("writeEmbed",function(){var a=F("PLAYER_CONFIG",void 0);if(!a){var b=F("PLAYER_VARS",void 0);b&&(a={args:b})}qm(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=F("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);M("embeds_js_api_set_1p_cookie")&&(c=ph(),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));L("FORCE_CSI_ON_GEL",!0);
c=["ol"];nn("").info.actionType="embed";c&&L("TIMING_AFT_KEYS",c);L("TIMING_ACTION","embed");c=F("TIMING_INFO",{});for(var d in c)c.hasOwnProperty(d)&&En(d,c[d]);En("is_nav",1);(d=Dm())&&En("csn",d);(d=F("PREVIOUS_ACTION",void 0))&&!zn()&&En("pa",d);d=hn();c=F("CLIENT_PROTOCOL");var e=F("CLIENT_TRANSPORT");c&&En("p",c);e&&En("t",e);En("yt_vis",Hn());En("yt_lt","cold");c=dn();if(e=fn())Z("srt",c.responseStart),1!==d.prerender&&(En("yt_sts","n",void 0),Z("_start",e,void 0));d=ln();0<d&&Z("fpt",d);d=
dn();d.isPerformanceNavigationTiming&&En("pnt",1,void 0);Z("nreqs",d.requestStart,void 0);Z("nress",d.responseStart,void 0);Z("nrese",d.responseEnd,void 0);0<d.redirectEnd-d.redirectStart&&(Z("nrs",d.redirectStart,void 0),Z("nre",d.redirectEnd,void 0));0<d.domainLookupEnd-d.domainLookupStart&&(Z("ndnss",d.domainLookupStart,void 0),Z("ndnse",d.domainLookupEnd,void 0));0<d.connectEnd-d.connectStart&&(Z("ntcps",d.connectStart,void 0),Z("ntcpe",d.connectEnd,void 0));d.secureConnectionStart>=fn()&&0<d.connectEnd-
d.secureConnectionStart&&(Z("nstcps",d.secureConnectionStart,void 0),Z("ntcpe",d.connectEnd,void 0));W&&W.getEntriesByType&&Jn();d=[];if(document.querySelector&&W&&W.getEntriesByName)for(var f in an)an.hasOwnProperty(f)&&(c=an[f],In(f,c)&&d.push(c));for(f=0;f<d.length;f++)En("rc",d[f]);if(zn(void 0)){f={actionType:tn[F("TIMING_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN",previousAction:tn[F("PREVIOUS_ACTION",void 0)]||"LATENCY_ACTION_UNKNOWN"};if(d=Dm())f.clientScreenNonce=d;d=jn(void 0);c=gn(void 0).cttAuthInfo;
rn().info(f,d,c)}f=hn();c=cn();if("cold"===f.yt_lt&&(d=Bn(),e=d.gelTicks?d.gelTicks:d.gelTicks={},d=d.gelInfos?d.gelInfos:d.gelInfos={},zn())){for(var g in c)"tick_"+g in e||An(g,c[g]);g=Dn();c=jn();e=gn().cttAuthInfo;var h={},k=!1,l;for(l in f)if(!("info_"+l in d)){var n=Cn(l,f[l]);n&&(Pm(g,n),Pm(h,n),k=!0)}k&&rn().info(h,c,e)}B("ytglobal.timingready_",!0,void 0);Fn();(l=F("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in l?(l=l.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,
l.serializedForcedExperimentIds||(g=ph(),g.forced_experiments&&(l.serializedForcedExperimentIds=g.forced_experiments)),np=lp(a,l,!1)):np=lp(a);np.addEventListener("onVideoDataChange",qp);a=F("POST_MESSAGE_ID","player");F("ENABLE_JS_API")?pp=new Bo(np):F("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(op=new Io(window.parent,a,b),pp=new Fo(np,op.connection));fo();M("networkless_logging_web_embedded")&&(M("embeds_web_enable_new_nwl")?El():nl());M("embeds_enable_ua_ch_polyfill")&&to()},
void 0);
var tp=yg(function(){Gn();var a=Bi.getInstance(),b=!!((Ei("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&df(document.body,"exp-invert-logo"))if(c&&!df(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!df(d,"inverted-hdpi")){var e=bf(d);cf(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&df(document.body,"inverted-hdpi")&&ef();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Ei(b)||0;d=c?d|67108864:
d&-67108865;0==d?delete Ai[b]:(c=d.toString(16),Ai[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in Ai)d.push(f+"="+encodeURIComponent(String(Ai[f])));zi(b,d.join("&"),63072E3,a.i,c)}Ln.h||(Ln.h=new Ln);a=Ln.h;f=16623;var g=void 0===g?{}:g;Object.values(am).includes(f)||(Yl(new Xi("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.h.push({rootVe:f,key:g.key||""});a.u=[];a.o=[];g.fb?On(a,f,g):Pn(a,f,g)}),up=yg(function(){np&&
np.sendAbandonmentPing&&np.sendAbandonmentPing();
F("PL_ATT")&&lo.dispose();for(var a=0,b=co.length;a<b;a++)$g.aa(co[a]);co.length=0;ao("//static.doubleclick.net/instream/ad_status.js");eo=!1;L("DCLKSTAT",0);(0,Zd)(pp,op);np&&(np.removeEventListener("onVideoDataChange",qp),np.destroy())});
window.addEventListener?(window.addEventListener("load",tp),window.addEventListener("unload",up)):window.attachEvent&&(window.attachEvent("onload",tp),window.attachEvent("onunload",up));Va("yt.abuse.player.botguardInitialized",C("yt.abuse.player.botguardInitialized")||mo);Va("yt.abuse.player.invokeBotguard",C("yt.abuse.player.invokeBotguard")||no);Va("yt.abuse.dclkstatus.checkDclkStatus",C("yt.abuse.dclkstatus.checkDclkStatus")||go);
Va("yt.player.exports.navigate",C("yt.player.exports.navigate")||sp);Va("yt.util.activity.init",C("yt.util.activity.init")||bh);Va("yt.util.activity.getTimeSinceActive",C("yt.util.activity.getTimeSinceActive")||eh);Va("yt.util.activity.setTimestamp",C("yt.util.activity.setTimestamp")||ch);}).call(this);
