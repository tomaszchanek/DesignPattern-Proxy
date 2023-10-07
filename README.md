# Proxy Design Pattern

## Definition

Proxy is a structural design pattern that lets you provide a substitute or placeholder for another object. A proxy controls access to the original object, allowing you to perform something either before or after the request gets through to the original object.

![img_1.png](src/img_1.png)

## Example
### Youtube videos caching

Simulating simplified caching process of downloading youtube movies. Two scenarios available:
- direct connection to YT service and every request is followed with move download
- connection through proxy class that stores movies once downloaded no to repeat the process

Last step is a comparison of times between both scenarios. All is mocked with random latency

![img.png](src/img.png)

## Other

- Example is from awesome website [Refactoring Guru](https://refactoring.guru)