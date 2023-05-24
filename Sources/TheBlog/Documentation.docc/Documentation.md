# ``SlothCreator``

Catalog sloths you find in nature and create new adorable virtual sloths.

## Overview

```swift
struct Sightseeing: Activity {
    func perform(with sloth: inout Sloth) -> Speed {
        sloth.energyLevel -= 10
        return .slow
    }
}
```

```objc
@interface Sloth : NSObject

- (NSInteger)sleepInHabitat:(Habitat *)food forNumberOfHours:(NSInteger)numberOfHours;

@end
```

``SlothCreator/Sloth/eat(_:quantity:)``

``Sloth/Color-swift.enum``

``Sloth/Color-c.class``

[Apple](https://www.apple.com)

| Sloth speed  | Description                           |
| ------------ | ------------------------------------- | 
| `slow`       | Moves slightly faster than a snail.   |
| `medium`     | Moves at an average speed.            |
| `fast`       | Moves faster than a hare.             |
| `supersonic` | Moves faster than the speed of sound. |

> Tip: Sloths require sustenance to perform activities.

\* Not a bulleted list item.

## Topics

### Creating sloths

- ``SlothGenerator``
- ``NameGenerator``
- ``Habitat``

### Caring for sloths

- ``Activity``
- ``CareSchedule``
- ``FoodGenerator``
- ``Sloth/Food``

### Schedule

- ``schedule``
