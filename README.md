# finance
def compound_interest(principal, rate, time):
    """
    Calculate compound interest.

    Args:
    principal: The initial investment amount.
    rate: The annual interest rate (in decimal).
    time: The number of years the money is invested for.

    Returns:
    The future value of the investment.
    """
    return principal * (1 + rate) ** time

# Example usage:
principal_amount = 1000  # initial investment amount
annual_interest_rate = 0.05  # 5% annual interest rate
investment_time = 5  # 5 years
future_value = compound_interest(principal_amount, annual_interest_rate, investment_time)
print("Future value of the investment:", future_value)
