<h1 align="center">:curly_loop: tether :link:</h1>
<h3 align="center">Drag & Drop DLL Proxy</h2>

## Usage
Include `tether.h` in your DLL project.

## Proxies
| Library | Procedures |
| ----------------------------------- | ------------- |
| dxgi.dll  | CreateDXGIFactory <br> CreateDXGIFactory1 <br> CreateDXGIFactory2 |
| dinput8.dll  | DirectInput8Create |
| d3d11.dll  | D3D11CreateDevice |

## Requirements
Depends on the proxies you want to use, but you'll probably always need the Windows SDK.

## Why does this exist?
The repo exists so I can quickly and easily clone and include it in projects instead of having to type/copy the same stuff every time.

## What if it doesn't have the proxy I'm looking for?
Look at the existing examples and add it. I'll also be happy to merge pull requests.
