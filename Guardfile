# A sample Guardfile
# More info at https://github.com/guard/guard#readme

## Uncomment and set this to only include directories you want to watch
# directories %(app lib config test spec feature)

## Uncomment to clear the screen before every task
# clearing :on

guard 'livereload' do
  watch(%r{_includes/.+\.(erb|haml|slim|html)$})
  watch(%r{_layouts/.+\.(erb|haml|slim|html)$})
  watch(%r{_posts/.+\.(md|markdown)})
  watch(%r{_sass/.+\.(scss)})
  watch(%r{css/.+\.(scss|css)})
end
