# The programmer's thesaurus
## Introduction
In computer-related areas, the English language offers a broad
vocabulary. Therefore, naming functions and methods can be a
difficult task. This document aims to be a comprehensive
reference which will help you finding the most appropriate word
in all situations.

If you want to contribute, we'd be happy to include your changes.
Please fork this repository and then send in a pull request.

## Variable, Property and Attribute names
### Language features
* arg, argument
* attr, attribute
* const, constant
* def, default
* func, function
* ident, identifier
* param, parameter
* spec, specifier
* var, variable

### Object-Orientation
* action
* class
* context
* dependency
* ident, identifier
* inheritance
* inst, instance
* itf, interface
* memb, member
* meth, method
* mod, module
* obj, object
* priv, private
* prop, property
* protected
* public
* published
* res, resource
* routine
* self
* shared
* this

### States
* hidden
* mutable
* transient
* volatile

### Loops, Lists and Arrays
* bucket
* el, elem, element
* i, idx, index
* it, item
* it, iter, iterator
* slot

### Tables
* col, column
* row

### Date/Time
* d, day
* date
* h, hour
* hrs, hours
* m, min, minute
* m, month
* mins, minutes
* time
* y, year

### Processes
* pid, processId
* proc, process

### Search
* needle
* haystack
* off, ofs, offset
* pos, position
* occurrence

### Trees
* child
* node
* parent
* path

### Graphical User Interfaces
* box
* dialog
* entry
* expose
* geometry
* opt, option
* widget

### Tasks and Operations
* action
* batch
* bulk
* job
* mass
* op, operation
* proc, process
* progress
* routine
* task

### Entities
* block
* bundle
* context
* entity
* group
* session
* transaction

### Event handling
* caller
* cb, callback
* context
* hook
* sender
* sig, signal
* subscr, subscriber

### Memory and Garbage Collection
* addr, address
* allocator
* arena
* block
* buf, buffer
* capacity
* chunk
* context
* mem, memory
* pool
* ptr, pointer
* refcnt, reference count
* segment
* size
* storage

### Networking
* chunk
* conn, connection
* host
* ip
* packet
* payload
* socket

### Web development
* cookie
* sess, session

### User Interfaces
* caption
* descr, description
* headline
* name
* pg, page
* title

### File
* directory
* eof, endOfFile
* file
* io
* path

### Data types/structures
* buf, buffer
* ptr, pointer
* str, string

### Links
* prev, next

### Debugging and Error handling
* bug
* crash
* err, error, errno
* exc, exception
* failure
* fix
* prio, priority
* st, status
* tc, test case
* tb, test bundle
* ts, test suite

### Messaging
* msg, message
* req, request
* resp, response

### Return values
* out, output
* res, result

### Lines
* eol, endOfLine
* bol, beginningOfLine

### Positions and lengths
* capacity
* cnt, count
* len, length
* off, offset
* pos, position
* size

### Database
* cur, current
* cur, cursor
* db, database
* qry, query
* record
* snapshot

### Binaries
* symtab, symbol table
* syms, symbols

### Time
* sec, s
* msec
* usec
* time
* diff, difference
* tz, timezone

### Characters and Strings
* buf, buffer
* c, ch: character
* cstr: C string
* len, length
* s, str: string
* sz: zero-terminated string

### General
* env, environment
* val, value

## Function names
### Object-Orientation
* depend
* inherit

### Event handling
* attach
* bind
* call
* conn, connect
* detach
* disconn, disconnect
* emit
* invoke
* notify
* observe
* pass
* register
* restore
* subscribe
* trigger
* unregister
* unsubscribe

### Database
* commit
* conn, connect
* disconn, disconnect
* populate
* qry, query

### ACL
* grant
* deny

### Test suites
* assert
* expect

### Serialising
* bundle
* escape
* obfuscate
* sanitise
* serialise
* wrap, unwrap

### Resizing
* enlarge
* extend
* grow
* resize

### Compression
* compress
* minimize
* shorten
* shrink

### Math
* rd, round
* rnd, random, randomize

### Strings
* append
* bind
* concat, concatenate
* format
* insert
* resize
* trim

### Loops, Lists and Arrays
* add
* bwd, backward
* each, foreach
* enum, enumerate
* find
* fwd, forward
* iter, iterate
* list
* lookup
* pop
* push
* remove
* rev, reverse
* rpt, repeat
* rwd, rewind

### Trees
* appendChild
* collapse
* createElement
* expand
* getChildren
* hasChildren
* setAttribute

### Templates
* assign
* display
* render

### Memory and Garbage Collection
* alloc, allocate
* dispose
* free
* invalidate
* link
* new
* ref, reference
* relate
* release
* retain
* steal
* unlink
* unref, unreference

### Networking
* accept
* addHandler, e.g. addEventHandler
* bind
* download
* handshake
* listen
* read
* recv, receive
* send, e.g. sendAuthRequest
* upload
* write

### Encoding
* decode
* decrypt
* encode
* encrypt
* mangle

### Graphical User Interfaces
* activate
* draw
* hide
* paint
* update

### Tasks and Operations
* continue
* handle
* hold
* invoke
* launch
* proceed
* process
* redo
* request
* reset
* respond
* restart
* resume
* run
* start
* stop
* suspend
* undo

### Processes
* exec, execute
* kill
* launch
* restart

### Receiving
* fetch
* get, e.g getName, getById
* grab
* obtain
* read
* recv, receive
* request
* retr, retrieve

### Transmission
* deliver
* send
* transfer
* transmit

### Clusters and Collections
* accumulate
* aggregate
* collect

### Iterating
* each, foreach
* getIter, getIterator
* iter, iterate
* key
* list
* map
* next
* prev
* reduce
* valid
* value
* walk

### Checking
* can
* has
* is

### ORM
* belongsTo
* hasOne
* hasMany

### Comparing
* cmp, compare
* contains
* diff
* eq, equals, isEqual
* matches

### Streams
* rewind
* tell
* peek

### File
* append
* lock
* open
* read
* unlock
* write

### Construction
* acquire
* alloc, allocate
* boot, bootstrap
* bootstrap
* build
* constr, construct
* create
* ctor, constructor
* decl, declare
* init, initialize
* install
* instantiate
* load, e.g. loadFile
* make
* new
* start

### Destruction
* cleanup
* clean
* clear
* close
* commit
* del, delete
* destroy
* destruct
* dispose
* drop
* dtor, destructor
* erase
* exit
* finalize
* free
* invalidate
* kill
* purge
* release
* rem, remove
* stop
* term, terminate
* uninstall
* unlink
* wipe

### Updating
* upd, update
* upgr, upgrade
* refr, refresh
* touch (updates timestamp to match current time)

### Merging
* apply
* combine
* concat, concatenate
* join
* merge

### Duplication
* cpy, copy
* clone
* dup, duplicate

### Assigning
* assign
* set

### Output
* pr, print
* echo
* write
* disp, display

### Search
* extract
* filter
* find, e.g. findRoute, rfind, reverseFind
* lookup
* match
* read
* scan
* search
* seek

### Error handling
* assert
* catch
* debug
* except
* expect
* getCode
* getFile
* getLine
* getMessage
* getTrace
* pass
* raise
* throw
* try

### Storage
* read
* save
* store

## Class names
* Abstract, e.g. AbstractManufacturer
* Batch
* Behavior
* ConcreteFilter
* Debugger
* Decorator
* Facade, e.g. PurchasingFacade
* Facade
* Factory
* Figure
* Filter
* FrontController: addPreFilter, addPostFilter, handleRequest
* Handler, e.g. RequestHandler
* Implementation
* Instance
* Interface
* Listener
* Manager
* Middleware
* Operation
* Processor
* Provider
* Proxy
* Registry
* Reporter
* Service
* Singleton
* Storage
* Utils

### Events
* EventDispatcher
* Observer

### Collections
* Chain, e.g. FilterChain
* Cluster
* Collection
* Container
* Repository
* Suite

### Components
* Component
* Kit
* Module
* Package

### Interface names
* Iterator: current, key, next, rewind, valid
* IteratorAggregate
* Observable: attach, detach, notify
* Processor
* Serializable

## Example: Car rental company
### Classes
* Vehicle
* Customer
* RentalAction

### Methods
* isReturned
* isVehicleAvailable
* rentVehicle
* sellVehicle
* returnVehicle
* startEngine
* stopEngine

### Variables
* returnDate
* markVehicleReturned
* rentalActions

### Exceptions
* VehicleNotAvailableException
* MileageLimitExceededException

## Processes
* connecting
* idling
* initialising
* lingering
* pending
* processing
* reading
* waiting
* writing

## States
* attached
* closed
* connected
* idle
* initialized
* listening
* paused
* readable
* stalled
* writable

## Roles
* Administrator
* Author
* Collaborator
* Contributor
* Editor
* Guest
* Manager
* Member
* Moderator
* Publisher
* Subscriber
* User
* Viewer

## VCS commit messages
This chapter introduces some rules for commit messages and
provides you with a few sample sentences which you can use in
your own commits.

### Rules
First of all, it's advisable to generally use the present tense
in the header in which you only give an abstract description of
your changes. For consistency, terminate all header messages
with a point. An exception is non-linguistic contents such as
commands, e.g. `s/needle/replace/`.

In the body you should go into detail. If appropriate,
may also want to give some background information.
Unlike the header, it's valid to use the past tense in
the body.

As for object-oriented projects, the general structure of
the header is:

```
Module: Message
```

When a commit affects multiple modules, you can enumerate them:

```
Module1, Module2: Message
```

Alternatively, the enumeration may be omitted if there are too
many.

### Deletion
* Delete *X*
* Get rid of *X*
* Drop *X* (e.g. *Drop support for X*)

### Bug fixing
* Fix *X*
* Fix bug
* Spotted with *X* (e.g. Valgrind) *This should go into the description.*

### Replacing components
* Make use of *X*.
* Merge *X* and *Y*
* Use *X* in favour of *Y*
* Use *X* instead of *Y*

### General changes
* Change *X*
* Cosmetic changes
* Enhance *X*
* Facilitate *X*
* Improve *X*
* Restore *X* (e.g. *Restore old behaviour*)
* Revert *X*
* Revise *X*
* Rework *X*
* Synchronise with upstream changes
* Trivial change(s)

## Logging levels
Sorted by severity:

* Trace
* Debug
* Informational
* Warning
* Error
* Critical
* Fatal

## Abbreviations
Each language has a certain number of words which appears to be
specific to it. This chapter collects unique technical
vocabulary grouped by the language it primarily occurs in. The
purpose is to help you discovering interesting concepts and to give
you some inspiration for making up your own ingenious class,
variable and function names.

### PHP
* `__autoload`
* `__construct`
* `__unset`
* trim
* implode
* explode
* needle
* haystack

### C
* strcmp, sometimes: streq
* argv, argc
* strlen
* strcpy
* strdup

### C++
* ctor
* dtor
* cstr

### Python
* `__init__`
* `__new__`

### Haskell
* map
* filter
* bind
* newtype

### Lua
* pairs, ipairs
* tonumber

### Ruby
* puts
* upcase
* times

### Java
* bean
* servlet
* datasource

## Authors
* Tim Nieradzik
* Will Hilton

## Credits
Most OO-related terms were taken from the book "PHP Design Patterns" by
Stephan Schmidt. Contributions were received from:

* Zachary Halbrecht

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
