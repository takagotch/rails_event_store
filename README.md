### rails_event_store
---
https://github.com/RailsEventStore/rails_event_store

https://railseventstore.org/docs/install/

```rb
// raise_event_store/ruby_event_store/spec/in_memory_repository_spec.rb

module RubyEventStore
  RSpec.describe InMemoryRepository do
    let(:test_race_conditions_any) { true }
    let(:test_race_conditions_auto) { true }
    let(:test_binary) { true }
    let(:test_change) { true }
    
    it_behaves_like :event_repository, InMeoryRepository
    
    it '' do
    end
  end
end



```

```
```

```
```

