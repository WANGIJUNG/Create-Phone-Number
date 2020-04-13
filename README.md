# Create-Phone-Number
Create Phone Number

JavaScript:
function createPhoneNumber(numbers){
  return numbers.join("").replace(/(...)(...)(.*)/,'($1) $2-$3')
}
