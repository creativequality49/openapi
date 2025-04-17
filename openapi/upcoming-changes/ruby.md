* Add support for `minority_owned_business_designation` on `Account::BusinessProfile`, `Account::CreateParams::BusinessProfile`, and `Account::UpdateParams::BusinessProfile`
* Add support for `registration_date` on `Account::Company`, `Account::CreateParams::Company`, `Account::UpdateParams::Company`, and `Token::CreateParams::Account::Company`
* Add support for `tax_id` on `Charge::BillingDetail`, `ConfirmationToken::CreateParams::PaymentMethodDatum::BillingDetail`, `ConfirmationToken::PaymentMethodPreview::BillingDetail`, `PaymentIntent::ConfirmParams::PaymentMethodDatum::BillingDetail`, `PaymentIntent::CreateParams::PaymentMethodDatum::BillingDetail`, `PaymentIntent::UpdateParams::PaymentMethodDatum::BillingDetail`, `PaymentMethod::BillingDetail`, `PaymentMethod::CreateParams::BillingDetail`, `PaymentMethod::UpdateParams::BillingDetail`, `SetupIntent::ConfirmParams::PaymentMethodDatum::BillingDetail`, `SetupIntent::CreateParams::PaymentMethodDatum::BillingDetail`, `SetupIntent::UpdateParams::PaymentMethodDatum::BillingDetail`, and `TreasuryOutboundPayment::CreateParams::DestinationPaymentMethodDatum::BillingDetail`
* Add support for `wallet_options` on `CheckoutSession::CreateParams` and `CheckoutSession`
* Add support for `payment_method_options` on `ConfirmationToken::CreateParams`
* Add support for `installments` on `ConfirmationToken::PaymentMethodOption::Card`
* Add support for `billie` on `PaymentIntent::ConfirmParams::PaymentMethodOption`, `PaymentIntent::CreateParams::PaymentMethodOption`, `PaymentIntent::PaymentMethodOption`, and `PaymentIntent::UpdateParams::PaymentMethodOption`
* Add support for `pix` on `PaymentMethodConfiguration::CreateParams`, `PaymentMethodConfiguration::UpdateParams`, and `PaymentMethodConfiguration`
* Add support for `klarna` on `PaymentMethodDomain`
* Add support for `us_cfpb_data` on `Person` and `Token::CreateParams::Person`
* Add support for `pending_reason` on `Refund`
* Change type of `TaxCalculationLineItem.reference` from `nullable(string)` to `string`
* Add support for `aw`, `az`, `bd`, `bj`, `et`, `in`, `kg`, `la`, and `ph` on `TaxRegistration::CountryOption` and `TaxRegistration::CreateParams::CountryOption`