# Addins List

  * [Anotar](https://github.com/Fody/Anotar) Simplifies logging through a static class and some IL manipulation.
  * [AsyncErrorHandler](https://github.com/Fody/AsyncErrorHandler) Integrates error handling into async and TPL code.
  * [AutoProperties](https://github.com/tom-englert/AutoProperties.Fody) Gives you extended control over auto-properties, like directly accessing the backing field or intercepting getters and setters.
  * [BasicFodyAddin](/BasicFodyAddin) A simple project meant to illustrate how to build an addin.
  * [Bindables](https://github.com/yusuf-gunaydin/Bindables) Converts your auto properties into Wpf dependency or attached properties. Allows specifying options, defining readonly properties, and calling property changed methods.
  * [Caseless](https://github.com/Fody/Caseless) Change string comparisons to be case insensitive.
  * [Catel](https://github.com/Catel/Catel.Fody) For transforming automatic properties into [Catel](https://github.com/Catel/Catel) properties.
  * [ConfigureAwait](https://github.com/Fody/ConfigureAwait) Allows you to set the async ConfigureAwait at a global level for all your await calls.
  * [Costura](https://github.com/Fody/Costura/) For embedding references as resources.
  * [EmptyConstructor](https://github.com/Fody/EmptyConstructor) Adds an empty constructor to classes even if a non empty one is defined.
  * [Equals](https://github.com/Fody/Equals) Generate Equals, GetHashCode and operators methods from properties.
  * [Equatable](https://github.com/tom-englert/Equatable.Fody) Generate Equals, GetHashCode and operators methods from explicit annotated fields and properties.
  * [ExtraConstraints](https://github.com/Fody/ExtraConstraints) Facilitates adding constraints for Enum and Delegate to types and methods.
  * [InfoOf](https://github.com/Fody/InfoOf) Provides `methodof`, `propertyof` and `fieldof` equivalents of [`typeof`](https://msdn.microsoft.com/en-us/library/58918ffs.aspx).
  * [InlineIL](https://github.com/ltrzesniewski/InlineIL.Fody) Provides a way to embed arbitrary IL instructions in existing code.
  * [Ionad](https://github.com/Fody/Ionad) Replaces static method calls.
  * [Janitor](https://github.com/Fody/Janitor) Simplifies the implementation of [IDisposable](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable).
  * [JetBrainsAnnotations](https://github.com/tom-englert/JetBrainsAnnotations.Fody) Converts all JetBrains ReSharper code annotation attributes to External Annotations.
  * [Lazy](https://github.com/tom-englert/Lazy.Fody) Automates the plumbing around System.Lazy.
  * [LoadAssembliesOnStartup](https://github.com/Fody/LoadAssembliesOnStartup) Loads references on startup by using the types in the module initializer.
  * [LocalsInit](https://github.com/ltrzesniewski/LocalsInit.Fody) Controls the value of the `localsinit` flag on methods, to improve the performance of `stackalloc` for instance.
  * [LoggerIsEnabled](https://github.com/wazowsk1/LoggerIsEnabled.Fody) Adds `ILogger.IsEnabled` check around the logging statement for the [Microsoft.Extensions.Logging](https://github.com/aspnet/Logging).
  * [MethodBoundaryAspect](https://github.com/vescon/MethodBoundaryAspect.Fody) Allows to decorate methods and hook into method start, method end and method exceptions (like PostSharp).
  * [MethodDecorator](https://github.com/Fody/MethodDecorator) Decorate arbitrary methods to run code before and after invocation.
  * [MethodTimer](https://github.com/Fody/MethodTimer) Injects method timing code.
  * [ModuleInit](https://github.com/Fody/ModuleInit) Adds a module initializer to an assembly.
  * [NullGuard](https://github.com/Fody/NullGuard) Adds null argument checks to an assembly.
  * [Obsolete](https://github.com/Fody/Obsolete) Helps keep usages of [ObsoleteAttribute]([https://msdn.microsoft.com/en-us/library/fwz0y5c2 ) consistent.
  * [PropertyChanged](https://github.com/Fody/PropertyChanged) Injects INotifyPropertyChanged code into properties.
  * [PropertyChanging](https://github.com/Fody/PropertyChanging) Injects INotifyPropertyChanging code into properties.
  * [Publicize](https://github.com/Fody/Publicize) Converts non-public members to public hidden members.
  * [Realm](https://github.com/realm/realm-dotnet) Mobile database: a replacement for SQLite & ORMs.
  * [ReactiveUI.Fody](https://github.com/reactiveui/ReactiveUI) Generates [ReactiveUI](https://reactiveui.net/) `RaisePropertyChanged` notifications for properties and `OAPH`s.
  * [Resourcer](https://github.com/Fody/Resourcer) Simplifies reading embedded resources from an Assembly.
  * [SplashScreen](https://github.com/tom-englert/SplashScreen.Fody) Lets you design your WPF splash screen as a WPF Control instead of a static bitmap.
  * [StampSvn](https://github.com/krk/Stamp) Stamps an assembly with SVN data.
  * [Substitute](https://github.com/tom-englert/Substitute.Fody) Substitute types with other types to e.g. intercept generated code.
  * [SwallowExceptions](https://github.com/duaneedwards/SwallowExceptions) Swallow Exceptions in targeted methods.
  * [Throttle](https://github.com/tom-englert/Throttle.Fody) Easily use throttles with minimal coding.
  * [ToString](https://github.com/Fody/ToString) Generate `ToString` method from public properties.
  * [Tracer](https://github.com/csnemes/tracer) Adds trace-enter and trace-leave log entries for selected methods.
  * [Undisposed](https://github.com/ermshiperete/undisposed-fody) Debugging tool to track down undisposed objects.
  * [Validar](https://github.com/Fody/Validar) Injects [IDataErrorInfo](https://docs.microsoft.com/en-us/dotnet/api/system.componentmodel.idataerrorinfo) or [INotifyDataErrorInfo](https://docs.microsoft.com/en-us/dotnet/api/system.componentmodel.inotifydataerrorinfo) code into a class at compile time.
  * [Vandelay](https://github.com/jasonwoods-7/Vandelay) Simplifies MEF importing\exporting.
  * [Visualize](https://github.com/Fody/Visualize) Adds debugger attributes to help visualize objects.
  * [Virtuosity](https://github.com/Fody/Virtuosity) Change all members to virtual.
  * [WeakEventHandler](https://github.com/tom-englert/WeakEventHandler.Fody) Changes regular event handlers into weak event handlers by weaving a weak event adapter between source and subscriber.
  * [WeakEvents](https://github.com/adbancroft/WeakEvents.Fody) Automatic publishing of weak events via compile time code weaving and a supporting runtime library.
  * [With](https://github.com/mikhailshilkov/With.Fody) Methods to return copies of immutable objects with one property modified.


## No longer maintained

The below addins are no longer maintained. Raise an issue in the specific project if you would like to take ownership.

  * [ArraySlice](https://github.com/Codealike/arrayslice) ArraySlice allows to build shared memory array views without performance impact. It uses IL manipulation to achieve the fastest implementation.
  * [AssertMessage](https://github.com/Fody/AssertMessage) Generates 'message' from sourcecode and adds it to assertion.
  * [AutoDependencyProperty](http://blog.angeloflogic.com/2014/12/no-more-dependencyproperty-with.html) Generates WPF DependencyProperty boilerplate from automatic C# properties.
  * [AutoLazy](https://github.com/bcuff/AutoLazy) Automatically implements the double-checked locking pattern on specified properties and methods.
  * [Cauldron](https://github.com/Capgemini/Cauldron) Provides method, property and field interception. It also provides weavers for Cauldron.Core and Cauldron.Activator.
  * [Cilador](https://github.com/rileywhite/Cilador) Write your own [mixins](https://en.wikipedia.org/wiki/Mixin) in C# for code reuse without inheritance.
  * [Commander](https://github.com/DamianReeves/Commander.Fody) Injects ICommand properties and implementations for use in MVVM applications.
  * [CryptStr](https://cryptstr.codeplex.com/) Encrypts literal strings in your .NET assemblies.
  * [DependencyInjection](https://github.com/jorgehmv/FodyDependencyInjection) automatic dependency injection for [Ninject](http://www.ninject.org/), [Autofac](http://autofac.org/) and [Spring](http://www.springframework.net/).
  * [EmptyStringGuard](https://github.com/thirkcircus/EmptyStringGuard) Adds empty string argument checks to an assembly.
  * [EnableFaking](https://github.com/philippdolder/EnableFaking.Fody) Allows faking your types without writing interfaces for testing purposes only.
  * [Expose](https://github.com/kedarvaidya/Expose.Fody) Exposes members and optionally implements interface of a field declared in class.
  * [FactoryId](https://github.com/ramoneeza/FactoryId.Fody) Simplifies the implementation of Factory Method Pattern.
  * [Fielder](https://github.com/fodyarchived/Fielder) Converts public fields to public properties.
  * [Freezable](https://github.com/fodyarchived/Freezable) Implements the Freezable pattern.
  * [Immutable](https://github.com/fodyarchived/Immutable) Creates immutable types.
  * [MethodCache](https://github.com/Dresel/MethodCache) Caches return values of methods decorated with a `CacheAttribute`.
  * [Mixins](https://bitbucket.org/skwasiborski/mixins.fody/wiki/Home) A mixin is a class that provides a certain functionality to be inherited or just reused by a subclass.
  * [Mutable](https://github.com/ndamjan/Mutable.Fody) Make F# setters for union types and eliminate need for `CLIMutable` attribute for records.
  * [Mvid](https://github.com/hmemcpy/Mvid.Fody) Adds the ability to specify the assembly MVID (Module Version Id).
  * [NameOf](https://github.com/NickStrupat/NameOf) Provides strongly typed access to a compile-time string representing the name of a variable, field, property, method, event, enum value, or type.
  * [Nancy.ModelPostprocess](https://bitbucket.org/tpluscode/nancy.modelpostprocess) Modify Nancy models after route execution but before serialization
  * [NObservable](https://github.com/kekekeks/NObservable) MobX-like observable state management library with Blazor support.
  * [Padded](https://github.com/Scooletz/Padded) Adds padding to fight the false sharing problem.
  * [QueryValidator](https://github.com/kamil-mrzyglod/QueryValidator.Fody) Validates your DB queries during a build.
  * [RemoveReference](https://github.com/icnocop/RemoveReference.Fody) Facilitates removing references in a compiled assembly during a build.
  * [RomanticWeb](http://romanticweb.net/) Fody weaver plugin for RomanticWeb instrumentation.
  * [Scalpel](https://github.com/Fody/Scalpel) Strips tests from an assembly.
  * [Seal](https://github.com/kamil-mrzyglod/Seal) mark all non-virtual(abstract, non-sealed) types as sealed by default.
  * [SexyProxy](https://github.com/kswoll/sexy-proxy) Proxy generator with support for async patterns.
  * [Spring](https://github.com/jorgehmv/FodySpring) Spring constructor configuration.
  * [Stamp](https://github.com/304NotModified/Fody.Stamp) Stamps an assembly with git data.
  * [StaticProxy](https://github.com/BrunoJuchli/StaticProxy.Fody) Proxy Generator, also for .net standard / .net core (.net standard 1.0+).
  * [Stiletto](https://github.com/benjamin-bader/stiletto) Compile-time static analysis and optimization for the Stiletto IoC library.
  * [Tail](https://github.com/hazzik/Tail.Fody) Adds a postfixed method call instruction to recursive calls.
  * [TestFlask](https://github.com/FatihSahin/test-flask) Records your method args and responses to replay, assert and test.
  * [Unsealed](https://github.com/fodyarchived/Unsealed) A simple Fody weaver to unseal sealed types.
  * [Usable](https://github.com/fodyarchived/Usable) Adds using statements for local variables that have been created, and implement [IDisposable](https://docs.microsoft.com/en-us/dotnet/api/system.idisposable).
  * [YALF](https://github.com/sharpmonkey/YALF) Yet Another Logging Framework.