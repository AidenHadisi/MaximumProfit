
#include<vector>
#include <iostream>
using namespace std;

/**
 * @brief Finds the maximum profit from buying and selling stocks.
 * @param prices An array for which the ith element is the price of a given stock on day i
 * @return The maximum profit possible
*/
int maximumProfit(std::vector<int>& prices) {
	
	int balance = 0;
	for (std::vector<int>::iterator it = prices.begin() + 1; it != prices.end(); it++) {

		//If price is increasing tomorrow: BUY today, SELL tomorrow
		if (*it > *(it - 1)) {
			balance += *it - *(it - 1);
			cout << "Buying for: " << *(it - 1) << " || Selling for:" << *it << " || Balance: " << balance << endl;
		}


	}

	return balance;
}
