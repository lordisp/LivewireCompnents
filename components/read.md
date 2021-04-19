simply use this by invoking the compnent inline in every place in your project 

```php
<livewire:components.edit-field :model="'\App\Models\User'" :entity="$user" :field="'name'" :key="'users'.$user->id"/>
```
