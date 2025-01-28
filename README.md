This repository demonstrates a subtle bug in using Elixir's `Enum.reduce` function with a conditional accumulation. The code attempts to sum only numbers greater than 3; however, it sums all numbers.  The solution provides a corrected approach using Enum.filter and Enum.sum for clarity and to avoid the unintended behavior.