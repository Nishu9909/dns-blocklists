resource "cloudflare_account_token" "example_account_token" {
  account_id = "276f1578b262185936cf4a94d5378698"
  name       = "throbbing-credit-1475"

  policies = [{
    effect = "allow"
    permission_groups = [{
      id = "cfa964bcdafc4ab39704e7476154e41b"
      }, {
      id = "dc44f27f48ab405392a5f69fe822bd01"
      }, {
      id = "1e13c5124ca64b72b1969a67e8829049"
      }, {
      id = "7ea222f6d5064cfa89ea366d7c1fee89"
      }, {
      id = "b9588b65fdc04d5f9170816e2fef96e2"
      }, {
      id = "ecbbebe25a014fa793d5226d6218303c"
      }, {
      id = "3f376c8e6f764a938b848bd01c8995c4"
      }, {
      id = "efb81b5cd37d49f3be1da9363a6d7a19"
      }, {
      id = "b33f02c6f7284e05a6f20741c0bb0567"
    }]
    resources = jsonencode({
      "com.cloudflare.api.account.276f1578b262185936cf4a94d5378698" = "*"
    })
  }]
}
