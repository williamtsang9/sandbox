

i = 5
while true
if i > 0
  puts 'This is my current i, ' +  i.to_s
  i -= 1
  sleep 1
elsif i == 0
  puts 'This is my current i, ' +  i.to_s
  i += 5
  sleep 1
  else 
    puts 'This is my current i, ' +  i.to_s
  i += 1
  sleep 1
end
end
