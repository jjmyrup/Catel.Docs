

# DependencyResolverExtensions

Name|Value
---|---
Assembly|Catel.Core
Namespace|Catel.IoC
Available on|.NET Framework 4.5, .NET Framework 4.6, Portable Class Libraries, Windows 10.0 (Universal Apps), Xamarin - Android, Xamarin - iOS

```
public static class DependencyResolverExtensions
```

Extensions for the [IDependencyResolver](#).



## Methods

### CanResolve<T>(IDependencyResolver dependencyResolver, object tag)

Determines whether the specified type with the specified tag can be resolved.

#### Type Parameters

**T**
The type to resolve.

#### Parameters

**dependencyResolver**
The dependency resolver.

**tag**
The tag.

#### Exceptions

**T:System.ArgumentNullException**
The dependencyResolver is ```null```.



### Resolve<T>(IDependencyResolver dependencyResolver, object tag)

Resolves the specified type with the specified tag.

#### Type Parameters

**T**
Tye type to resolve.

#### Parameters

**dependencyResolver**
The dependency resolver.

**tag**
The tag.

#### Returns

The resolved object.

#### Exceptions

**T:System.ArgumentNullException**
The dependencyResolver is ```null```.



### TryResolve(IDependencyResolver dependencyResolver, Type serviceType, object tag)

Try to resolve the specified type with the specified tag.

#### Parameters

**dependencyResolver**
The dependency resolver.

**serviceType**
Type of the service.

**tag**
The tag.

#### Returns

The resolved object or ```null``` if the type could not be resolved.

#### Exceptions

**T:System.ArgumentNullException**
The dependencyResolver is ```null```.



### TryResolve<T>(IDependencyResolver dependencyResolver, object tag)

Try to resolve the specified type with the specified tag.

#### Type Parameters

**T**
The type to resolve.

#### Parameters

**dependencyResolver**
The dependency resolver.

**tag**
The tag.

#### Returns

The resolved object or ```null``` if the type could not be resolved.

#### Exceptions

**T:System.ArgumentNullException**
The dependencyResolver is ```null```.


