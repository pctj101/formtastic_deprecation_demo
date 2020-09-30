# README

- https://github.com/formtastic/formtastic/issues/1314
- chruby 2.7.1
- mysqldump in ft.sql
- rails s
- uname -a -> Darwin dev.local 19.6.0 Darwin Kernel Version 19.6.0: Mon Aug 31 22:12:52 PDT 2020; root:xnu-6153.141.2~1/RELEASE_X86_64 x86_64

```
Started GET "/admin" for ::1 at 2020-09-30 21:14:29 +0900
Processing by Admin::DashboardController#index as HTML
  Rendering /Users/dev/.gem/ruby/2.7.1/gems/activeadmin-2.8.1/app/views/active_admin/page/index.html.arb
  Rendered /Users/dev/.gem/ruby/2.7.1/gems/activeadmin-2.8.1/app/views/active_admin/page/index.html.arb (Duration: 5.2ms | Allocations: 2708)
Completed 200 OK in 10ms (Views: 6.8ms | ActiveRecord: 0.0ms | Allocations: 4323)


Started GET "/admin/animals" for ::1 at 2020-09-30 21:14:31 +0900
Processing by Admin::AnimalsController#index as HTML
  Rendering /Users/dev/.gem/ruby/2.7.1/gems/activeadmin-2.8.1/app/views/active_admin/resource/index.html.arb
   (0.3ms)  SELECT COUNT(*) FROM (SELECT 1 AS one FROM `animals` LIMIT 30 OFFSET 0) subquery_for_count
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/i18n.rb:26: warning: Using the last argument as keyword parameters is deprecated; maybe ** should be added to the call
/Users/dev/.gem/ruby/2.7.1/gems/i18n-1.8.5/lib/i18n.rb:195: warning: The called method `translate' is defined here
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:104: warning: Using the last argument as keyword parameters is deprecated; maybe ** should be added to the call
/Users/dev/.gem/ruby/2.7.1/gems/i18n-1.8.5/lib/i18n.rb:195: warning: The called method `t' is defined here
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
/Users/dev/.gem/ruby/2.7.1/gems/formtastic-3.1.5/lib/formtastic/localizer.rb:118: warning: deprecated Object#=~ is called on FalseClass; it always returns nil
  Rendered /Users/dev/.gem/ruby/2.7.1/gems/activeadmin-2.8.1/app/views/active_admin/resource/index.html.arb (Duration: 28.4ms | Allocations: 19421)
Completed 200 OK in 41ms (Views: 30.4ms | ActiveRecord: 1.5ms | Allocations: 24181)
```
