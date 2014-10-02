12456122
========

First assignment for daniel sheridan
Skippy assignment


class Die

  def direction
    random = 1+rand(4)
    if random == 1
      @direction = "North"

    elsif random == 2
      @direction = "South"

    elsif random == 3
      @direction = "East"

    else
      @direction == "West"

    end
  end

def print
    puts "#{@direction}"

  end
  
  object = Die.new
  object.direction
  object.print

end
