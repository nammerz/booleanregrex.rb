booleanregrex.rb
================
def has_a_b?(string)
	if string =~ /b/
		puts "cha ching!"
	else
		puts "you missed out"
	end
end

has_a_b? ("earth")
has_a_b? ("marry poppins")
has_a_b? ("shotgun")
has_a_b? ("baluga")
