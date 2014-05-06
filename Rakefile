require 'slippery'
Slippery::RakeTasks.new do |s|

    s.options = {
      type: :reveal_js,
      theme: 'serif'
    }

    s.processor 'head' do |head|
      head <<= H[:title, 'The treasures of Ruby core, one for each day']
    end

    s.include_assets
    s.add_highlighting
end