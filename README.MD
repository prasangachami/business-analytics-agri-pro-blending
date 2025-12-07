Blending problem of Ari-pro

Agri-Pro has received an order for 8,000 pounds of chicken feed to be mixed from the feeds indicated in the table below.
The order must contain at least 
  20% corn, 
  15% grain,
  15% minerals

Decision variables:
– Xi : pounds of feed i to use in the mix, i=1,2,3,4

                  Percent of Nutrient in
Nutrient       Feed 1   Feed 2   Feed 3   Feed 4
Corn             30%      5%     20%       10%
Grain            10%     30%     15%       10%
Minerals         20%     20%     20%       30%
Cost per pound   $0.25   $0.30   $0.32     $0.15

(1) Minimise the total cost of filling the order:
    Min 0.25X1 + 0.30X2 + 0.32X3 + 0.15X4

(2) Produce 8,000 pounds of feed:
    X1 + X2 + X3 + X4 = 8,000

(3) Mix consists of at least 20% corn:
    (0.3X1 + 0.05X2 + 0.2X3 + 0.1X4)/8000 ≥ 0.2
(4) Mix consists of at least 15% grain
    (0.1X1 + 0.3X2 + 0.15X3 + 0.1X4)/8000 ≥ 0.15
(5) Mix consists of at least 15% minerals
    (0.2X1 + 0.2X2 + 0.2X3 + 0.3X4)/8000 ≥ 0.15
(6) Non-negativity conditions
    X1, X2, X3, X4 ≥ 0


