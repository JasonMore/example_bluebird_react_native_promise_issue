# example_bluebird_react_native_promise_issue
```
➜  example_bluebird_react_native_promise_issue git:(master) flow
[No file]:0
inconsistent use of library definitions
120:   static cast<T>(value: $Promisable<T>): Bluebird$Promise<T>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ undefined. This type is incompatible with. See lib: flow-typed/npm/bluebird_v3.x.x.js:120
120:   static cast<T>(value: $Promisable<T>): Bluebird$Promise<T>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ some incompatible instantiation of `T`. See lib: flow-typed/npm/bluebird_v3.x.x.js:120

[No file]:0
inconsistent use of library definitions
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ function type. This type is incompatible with an argument type of. See lib: flow-typed/npm/bluebird_v3.x.x.js:132
 24:     onFulfill?: ?(value: R) => Promise<U> | ?U,
                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ null. See lib: node_modules/react-native/flow/Promise.js:24

[No file]:0
inconsistent use of library definitions
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
                                                                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ function type. This type is incompatible with an argument type of. See lib: flow-typed/npm/bluebird_v3.x.x.js:132
 25:     onReject?: ?(error: any) => Promise<U> | ?U
                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ null. See lib: node_modules/react-native/flow/Promise.js:25

[No file]:0
inconsistent use of library definitions
136:   done<U>(onFulfill?: (value: R) => mixed, onReject?: (error: any) => mixed): void;
                           ^^^^^^^^^^^^^^^^^^^ function type. This type is incompatible with an argument type of. See lib: flow-typed/npm/bluebird_v3.x.x.js:136
 40:     onFulfill?: ?(value: R) => mixed,
                     ^^^^^^^^^^^^^^^^^^^^ null. See lib: node_modules/react-native/flow/Promise.js:40

[No file]:0
inconsistent use of library definitions
136:   done<U>(onFulfill?: (value: R) => mixed, onReject?: (error: any) => mixed): void;
                                                           ^^^^^^^^^^^^^^^^^^^^^ function type. This type is incompatible with an argument type of. See lib: flow-typed/npm/bluebird_v3.x.x.js:136
 41:     onReject?: ?(error: any) => mixed
                    ^^^^^^^^^^^^^^^^^^^^^^ null. See lib: node_modules/react-native/flow/Promise.js:41

[No file]:0
inconsistent use of library definitions
 24:     onFulfill?: ?(value: R) => Promise<U> | ?U,
                                                 ^^ null. This type is incompatible with. See lib: node_modules/react-native/flow/Promise.js:24
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ some incompatible instantiation of `U`. See lib: flow-typed/npm/bluebird_v3.x.x.js:132

[No file]:0
inconsistent use of library definitions
 24:     onFulfill?: ?(value: R) => Promise<U> | ?U,
                                                 ^^ undefined. This type is incompatible with. See lib: node_modules/react-native/flow/Promise.js:24
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ some incompatible instantiation of `U`. See lib: flow-typed/npm/bluebird_v3.x.x.js:132

[No file]:0
inconsistent use of library definitions
 25:     onReject?: ?(error: any) => Promise<U> | ?U
                                                  ^^ null. This type is incompatible with. See lib: node_modules/react-native/flow/Promise.js:25
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ some incompatible instantiation of `U`. See lib: flow-typed/npm/bluebird_v3.x.x.js:132

[No file]:0
inconsistent use of library definitions
 25:     onReject?: ?(error: any) => Promise<U> | ?U
                                                  ^^ undefined. This type is incompatible with. See lib: node_modules/react-native/flow/Promise.js:25
132:   then<U>(onFulfill?: (value: R) => $Promisable<U>, onReject?: (error: any) => $Promisable<U>): Bluebird$Promise<U>;
       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ some incompatible instantiation of `U`. See lib: flow-typed/npm/bluebird_v3.x.x.js:132


Found 9 errors
```
