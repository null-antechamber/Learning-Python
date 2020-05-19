##Ground Shipping Code ##

def ground_shipping(weight):
  if weight <= 2:
    return weight * 1.50 + 20.00
  elif weight > 2 and weight <= 6:
    return weight * 3.00 + 20
  elif weight > 6 and weight <= 10:
    return weight * 4.00 + 20
  else:
    return weight * 4.75 + 20

print(ground_shipping(8.4))

## Premium Ground Shipping Variable Storage ##

premium_ground = 125

## Drone Shipping Code ##

def drone_shipping(weight):
  if weight <= 2:
    return weight * 4.50
  elif weight > 2 and weight <= 6:
    return weight * 9
  elif weight > 6 and weight <= 10:
    return weight * 12
  else:
    return weight * 14.25

print(drone_shipping(1.5))


## Best Shipping Price ##

def shipping_price(weight):
  if drone_shipping(weight) < premium_ground and drone_shipping(weight) < ground_shipping(weight):
    return "The Cheapest Shipping is by Drone, and it will cost $" + str(drone_shipping(weight))
  if ground_shipping(weight) < drone_shipping(weight) and ground_shipping(weight) < premium_ground:
     return "The Cheapest Shipping is By Ground, and it will cost $" +str(ground_shipping(weight))
  else:
    return "The Cheapest Shipping is Premium Ground, and it will cost $" + str(premium_ground)

print(shipping_price(4.8))
print(shipping_price(41.5))

