# Laravel Shopping Cart
A Shopping Cart Implementation for Laravel Framework

## INSTALLATION

Install the package through [Composer](http://getcomposer.org/).

```php
composer require yasinsvr/cart
```

## CONFIGURATION

1. Open config/app.php and add this line to your Service Providers Array.

```php
YasinSVR\Cart\CartServiceProvider::class
```

2. Open config/app.php and add this line to your Aliases

```php
  'Cart' => YasinSVR\Cart\Facades\CartFacade::class
```

3. Optional configuration file (useful if you plan to have full control)

```php
php artisan vendor:publish --provider="YasinSVR\Cart\CartServiceProvider" --tag="config"
```

## License

The Laravel Shopping Cart is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

### Disclaimer

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR, OR ANY OF THE CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
"# cart" 
"# cart" 
