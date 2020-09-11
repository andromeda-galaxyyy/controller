COMPILE_DEPS = CORE_DEPS + JACKSON + REST + KRYO + CLI + [
    "//core/common:onos-core-common",
    "@minimal_json//:minimal_json",
]

osgi_jar_with_tests(
    suppress_checkstyle = True,
    deps = COMPILE_DEPS,
)

#REQUIRE_APPS = [
#    #    "org.onosproject.proxyarp",
#    "com.eclipsesource.json.JsonArray",
#]

onos_app(
    category = "Self defined onos",
    description = "Project demo",
    #    required_apps = REQUIRE_APPS,
    title = "Orlo Myonos",
    url = "http://onosproject.org",
)
