load("@rules_go//go:def.bzl", "go_library")
load("@gazelle//:def.bzl", "gazelle", "gazelle_binary")

go_library(
	name = "extension"
)

gazelle_binary(
	name = "my_gazelle_binary",
	languages = [
		":extension"
	],
)

gazelle(
	name = "my_gazelle",
	gazelle = ":my_gazelle_binary",
)