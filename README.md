# Angular-Tips

if ($scope.$root.$$phase != '$apply' && $scope.$root.$$phase != '$digest') {
	$scope.$apply();
}
